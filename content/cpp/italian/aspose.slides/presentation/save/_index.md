---
title: Save()
second_title: Riferimento API Aspose.Slides per C++
description: Salva tutte le diapositive di una presentazione in un file con il formato specificato.
type: docs
weight: 443
url: /it/aspose.slides/presentation/save/
---
## Presentation::Save(System::String, Export::SaveFormat) metodo


Salva tutte le diapositive di una presentazione in un file con il formato specificato.

```cpp
void Aspose::Slides::Presentation::Save(System::String fname, Export::SaveFormat format) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Percorso del file creato. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato dei dati esportati. |

## Presentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) metodo


Salva tutte le diapositive di una presentazione in un flusso nel formato specificato.

```cpp
void Aspose::Slides::Presentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flusso di output. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato dei dati esportati. |

## Presentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) metodo


Salva tutte le diapositive di una presentazione in un file con il formato specificato e con opzioni aggiuntive.

```cpp
void Aspose::Slides::Presentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Percorso del file creato. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Formato dei dati esportati. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Opzioni di formato aggiuntive. |
## Osservazioni



Il seguente esempio mostra come convertire PowerPoint in HTML utilizzando C++. 
```cpp
// Istanzia un oggetto presentazione che rappresenta un file di presentazione, ad esempio PPT, PPTX, ODP ecc.
auto presentation = System::MakeObject<Presentation>(u"Convert_HTML.pptx");

System::SharedPtr<HtmlOptions> htmlOpt = System::MakeObject<HtmlOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> options = System::MakeObject<NotesCommentsLayoutingOptions>();
options->set_NotesPosition(NotesPositions::BottomFull);
htmlOpt->set_SlidesLayoutOptions(options);
htmlOpt->set_HtmlFormatter(HtmlFormatter::CreateDocumentFormatter(u"", false));

// Saves the presentation to HTML
presentation->Save(u"ConvertWholePresentationToHTML_out.html", SaveFormat::Html, htmlOpt);
```
 Il seguente esempio mostra come convertire PowerPoint in HTML reattivo utilizzando C++. 
```cpp
// Istanzia un oggetto Presentation che rappresenta un file di presentazione
auto presentation = System::MakeObject<Presentation>(u"Convert_HTML.pptx");

System::SharedPtr<ResponsiveHtmlController> controller = System::MakeObject<ResponsiveHtmlController>();
System::SharedPtr<HtmlOptions> htmlOptions = System::MakeObject<HtmlOptions>();
htmlOptions->set_HtmlFormatter(HtmlFormatter::CreateCustomFormatter(controller));

// Salva la presentazione in HTML
presentation->Save(u"ConvertPresentationToResponsiveHTML_out.html", SaveFormat::Html, htmlOptions);
```
 Il seguente esempio mostra come convertire PowerPoint in HTML con note utilizzando C++. 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");

auto opt = System::MakeObject<HtmlOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> options = System::MakeObject<NotesCommentsLayoutingOptions>();
options->set_NotesPosition(NotesPositions::BottomFull);
opt->set_SlidesLayoutOptions(options);

// Salva le pagine delle note
pres->Save(u"Output.html", SaveFormat::Html, opt);
```
 Il seguente esempio mostra come convertire PowerPoint in HTML con caratteri originali utilizzando C++. 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

// Esclude i font di presentazione predefiniti
System::ArrayPtr<System::String> fontNameExcludeList = System::MakeArray<System::String>({u"Calibri", u"Arial"});
auto embedFontsController = System::MakeObject<EmbedAllFontsHtmlController>(fontNameExcludeList);
auto htmlOptionsEmbed = System::MakeObject<HtmlOptions>();
htmlOptionsEmbed->set_HtmlFormatter(HtmlFormatter::CreateCustomFormatter(embedFontsController));
pres->Save(u"input-PFDinDisplayPro-Regular-installed.html", SaveFormat::Html, htmlOptionsEmbed);
```
 Il seguente esempio mostra come convertire PowerPoint in HTML con immagini ad alta qualità a 150 DPI utilizzando C++. 
```cpp
auto pres = System::MakeObject<Presentation>(u"InputDoc.pptx");

auto htmlOpts = System::MakeObject<HtmlOptions>();
htmlOpts->set_PicturesCompression(PicturesCompression::Dpi150);

pres->Save(u"OutputDoc-dpi150.html", SaveFormat::Html, htmlOpts);
```
 Il seguente esempio mostra come convertire PowerPoint in HTML con immagini di qualità completa utilizzando C++. 
```cpp
auto pres = System::MakeObject<Presentation>(u"InputDoc.pptx");

auto htmlOpts = System::MakeObject<HtmlOptions>();
htmlOpts->set_DeletePicturesCroppedAreas(false);

pres->Save(u"Outputdoc-noCrop.html", SaveFormat::Html, htmlOpts);
```
 Il seguente esempio mostra come convertire [Slide](../../slide/) in HTML utilizzando C++. 
```cpp
```
 The following example shows how to save CSS and [Images](../../images/) when exporting To HTML using C++. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto htmlController = System::MakeObject<CustomHeaderAndFontsController>(u"styles.css");
auto options = System::MakeObject<HtmlOptions>();
options->set_HtmlFormatter(HtmlFormatter::CreateCustomFormatter(htmlController));
pres->Save(u"pres.html", SaveFormat::Html, options);
```

```cpp
class CustomHeaderAndFontsController : public EmbedAllFontsHtmlController
{
public:
    CustomHeaderAndFontsController(System::String cssFileName);
    void WriteDocumentStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IPresentation> presentation) override;
    void WriteAllFonts(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IPresentation> presentation) override;

private:
    static const System::String ms_header;
    System::String m_cssFileName;
};

const System::String CustomHeaderAndFontsController::ms_header = System::String(u"<!DOCTYPE html>\n") +
                                                                 u"<html>\n" + u"<head>\n" +
                                                                 u"<meta http-equiv=\"Content-Type\" content=\"text/html; charset=UTF-8\">\n" +
                                                                 u"<meta http-equiv=\"X-UA-Compatible\" content=\"IE=9\">\n" +
                                                                 u"<link rel=\"stylesheet\" type=\"text/css\" href=\"{0}\">\n" +
                                                                 u"</head>";

CustomHeaderAndFontsController::CustomHeaderAndFontsController(System::String cssFileName) : m_cssFileName(cssFileName)
{}

void CustomHeaderAndFontsController::WriteDocumentStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IPresentation> presentation)
{
    generator->AddHtml(System::String::Format(ms_header, m_cssFileName));
    WriteAllFonts(generator, presentation);
}

void CustomHeaderAndFontsController::WriteAllFonts(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IPresentation> presentation)
{
    generator->AddHtml(u"<!-- Embedded fonts -->");
    EmbedAllFontsHtmlController::WriteAllFonts(generator, presentation);
}
```
 The following example shows how to link all fonts when converting [Presentation](../) to HTML using C++. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

// Excludes default presentation fonts
System::ArrayPtr<System::String> fontNameExcludeList = System::MakeArray<System::String>({u"Calibri", u"Arial"});
auto linkcont = System::MakeObject<LinkAllFontsHtmlController>(fontNameExcludeList, u"C:\\Windows\\Fonts\\");
auto htmlOptionsEmbed = System::MakeObject<HtmlOptions>();
htmlOptionsEmbed->set_HtmlFormatter(HtmlFormatter::CreateCustomFormatter(linkcont));
pres->Save(u"pres.html", SaveFormat::Html, htmlOptionsEmbed);
```
 The following example shows how to LinkAllFontsHtmlController is implemented using C++. 
```cpp
class LinkAllFontsHtmlController : public EmbedAllFontsHtmlController
{
public:
    LinkAllFontsHtmlController(System::ArrayPtr<System::String> fontNameExcludeList, System::String basePath);
    void WriteFont(System::SharedPtr<IHtmlGenerator> generator,
                   System::SharedPtr<IFontData> originalFont,
                   System::SharedPtr<IFontData> substitutedFont,
                   System::String fontStyle,
                   System::String fontWeight,
                   System::ArrayPtr<uint8_t> fontData) override;

private:
    System::String m_basePath;
};

LinkAllFontsHtmlController::LinkAllFontsHtmlController(System::ArrayPtr<System::String> fontNameExcludeList, System::String basePath)
    : EmbedAllFontsHtmlController(fontNameExcludeList), m_basePath(basePath)
{}

void LinkAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator,
                                           System::SharedPtr<IFontData> originalFont,
                                           System::SharedPtr<IFontData> substitutedFont,
                                           System::String fontStyle,
                                           System::String fontWeight,
                                           System::ArrayPtr<uint8_t> fontData)
{
    try
    {
        System::String fontName = substitutedFont == nullptr ? originalFont->get_FontName() : substitutedFont->get_FontName();
        System::String path = fontName + u".woff";

        // Some path sanitize may be needed
        System::IO::File::WriteAllBytes(System::IO::Path::Combine(m_basePath, path), fontData);
        generator->AddHtml(u"<style>");
        generator->AddHtml(u"@font-face { ");
        generator->AddHtml(System::String(u"font-family: '") + fontName + u"'; ");
        generator->AddHtml(System::String(u"src: url('") + path + u"')");
        generator->AddHtml(u" }");
        generator->AddHtml(u"</style>");
    }
    catch (System::Exception& ex)
    {
        System::Console::WriteLine(ex->get_Message());
    }
}
```
 The following example shows how to convert PowerPoint to responsive HTML using C++. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto saveOptions = System::MakeObject<HtmlOptions>();
saveOptions->set_SvgResponsiveLayout(true);
presentation->Save(u"SomePresentation-out.html", SaveFormat::Html, saveOptions);
```
 Il seguente esempio mostra come esportare file multimediali in HTML usando C++. 
```cpp
// Loads a presentation
auto pres = System::MakeObject<Presentation>();

System::String path = u"C:/out/";
const System::String fileName = u"ExportMediaFiles_out.html";
const System::String baseUri = u"http://www.example.com/";
auto fileStream = System::MakeObject<System::IO::FileStream>(u"my_video.avi", System::IO::FileMode::Open, System::IO::FileAccess::Read);

auto video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::ReadStreamAndRelease);
auto slide = pres->get_Slides()->idx_get(0);
slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
auto controller = System::MakeObject<VideoPlayerHtmlController>(path, fileName, baseUri);

// Sets HTML options
System::SharedPtr<HtmlOptions> htmlOptions = System::MakeObject<HtmlOptions>(controller);
System::SharedPtr<SVGOptions> svgOptions = System::MakeObject<SVGOptions>(controller);
htmlOptions->set_HtmlFormatter(HtmlFormatter::CreateCustomFormatter(controller));
htmlOptions->set_SlideImageFormat(SlideImageFormat::Svg(svgOptions));

// Saves the file
pres->Save(System::IO::Path::Combine(path, fileName), SaveFormat::Html, htmlOptions);
```

## Presentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method


Saves all slides of a presentation to a stream in the specified format and with additional options.

```cpp
void Aspose::Slides::Presentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Output stream. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format of the exported data. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Additional format options. |

## Presentation::Save(System::SharedPtr\<Export::Xaml::IXamlOptions\>) method


Saves all slides of a presentation to a set of files representing XAML markup.

```cpp
void Aspose::Slides::Presentation::Save(System::SharedPtr<Export::Xaml::IXamlOptions> options) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\> | The XAML format options. |
## Remarks



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```

## Presentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat) method


Saves specified slides of a presentation to a file with the specified format with page number keeping.

```cpp
void Aspose::Slides::Presentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Path to the created file. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format of the exported data. |

## Presentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method


Saves specified slides of a presentation to a file with the specified format with page number keeping.

```cpp
void Aspose::Slides::Presentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Path to the created file. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format of the exported data. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Additional format options. |

## Presentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat) method


Saves specified slides of a presentation to a stream in the specified format with page number keeping.

```cpp
void Aspose::Slides::Presentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Output stream. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format of the exported data. |

## Presentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method


Saves specified slides of a presentation to a stream in the specified format with page number keeping.

```cpp
void Aspose::Slides::Presentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Output stream. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array with slide positions, starting from 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format of the exported data. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Additional format options. |
## Remarks



The following example shows how to convert PowerPoint to PNG. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto slide = pres->get_Slides()->idx_get(index);
    slide->GetThumbnail()->Save(System::String::Format(u"slide_{0}.png", index),
                                System::Drawing::Imaging::ImageFormat::get_Png());
}
```
 The following example shows how to convert PowerPoint to PNG with custom dimensions. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

float scaleX = 2.0f, scaleY = 2.0f;
for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto slide = pres->get_Slides()->idx_get(index);
    slide->GetThumbnail(scaleX, scaleY)->Save(System::String::Format(u"slide_{0}.png", index),
                                              System::Drawing::Imaging::ImageFormat::get_Png());
}
```
 The following example shows how to convert PowerPoint to PNG with custom size. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::Drawing::Size size(960, 720);
for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto slide = pres->get_Slides()->idx_get(index);
    slide->GetThumbnail(size)->Save(System::String::Format(u"slide_{0}.png", index),
                                    System::Drawing::Imaging::ImageFormat::get_Png());
}

## Vedi anche

* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [Presentation](../)
* Classe [Stream](../../../system.io/stream/)
* Classe [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Classe [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)