---
title: Save()
second_title: Aspose.Slides C++ API 参考
description: 将演示文稿的所有幻灯片保存为具有指定格式的文件。
type: docs
weight: 443
url: /zh/aspose.slides/presentation/save/
---
## Presentation::Save(System::String, Export::SaveFormat) 方法


将演示文稿的所有幻灯片保存到具有指定格式的文件中。

```cpp
void Aspose::Slides::Presentation::Save(System::String fname, Export::SaveFormat format) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | 创建的文件路径。 |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | 导出数据的格式。 |

## Presentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) 方法


将演示文稿的所有幻灯片保存到指定格式的流中。

```cpp
void Aspose::Slides::Presentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 输出流。 |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | 导出数据的格式。 |

## Presentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) 方法


将演示文稿的所有幻灯片保存到具有指定格式并带有附加选项的文件中。

```cpp
void Aspose::Slides::Presentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | 创建的文件路径。 |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | 导出数据的格式。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | 附加的格式选项。 |
## 备注



以下示例展示了如何使用 C++ 将 PowerPoint 转换为 HTML。 
```cpp
// 实例化一个表示演示文件（例如 PPT、PPTX、ODP 等）的演示对象
auto presentation = System::MakeObject<Presentation>(u"Convert_HTML.pptx");

System::SharedPtr<HtmlOptions> htmlOpt = System::MakeObject<HtmlOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> options = System::MakeObject<NotesCommentsLayoutingOptions>();
options->set_NotesPosition(NotesPositions::BottomFull);
htmlOpt->set_SlidesLayoutOptions(options);
htmlOpt->set_HtmlFormatter(HtmlFormatter::CreateDocumentFormatter(u"", false));

// 将演示文稿保存为 HTML
presentation->Save(u"ConvertWholePresentationToHTML_out.html", SaveFormat::Html, htmlOpt);
```
 以下示例展示了如何使用 C++ 将 PowerPoint 转换为响应式 HTML。 
```cpp
// 实例化一个表示演示文件的 Presentation 对象
auto presentation = System::MakeObject<Presentation>(u"Convert_HTML.pptx");

System::SharedPtr<ResponsiveHtmlController> controller = System::MakeObject<ResponsiveHtmlController>();
System::SharedPtr<HtmlOptions> htmlOptions = System::MakeObject<HtmlOptions>();
htmlOptions->set_HtmlFormatter(HtmlFormatter::CreateCustomFormatter(controller));

// 将演示文稿保存为 HTML
presentation->Save(u"ConvertPresentationToResponsiveHTML_out.html", SaveFormat::Html, htmlOptions);
```
 以下示例展示了如何使用 C++ 将 PowerPoint 转换为带有备注的 HTML。 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");

auto opt = System::MakeObject<HtmlOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> options = System::MakeObject<NotesCommentsLayoutingOptions>();
options->set_NotesPosition(NotesPositions::BottomFull);
opt->set_SlidesLayoutOptions(options);

// 保存备注页面
pres->Save(u"Output.html", SaveFormat::Html, opt);
```
 以下示例展示了如何使用 C++ 将 PowerPoint 转换为带有原始字体的 HTML。 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

// 排除默认演示文稿字体
System::ArrayPtr<System::String> fontNameExcludeList = System::MakeArray<System::String>({u"Calibri", u"Arial"});
auto embedFontsController = System::MakeObject<EmbedAllFontsHtmlController>(fontNameExcludeList);
auto htmlOptionsEmbed = System::MakeObject<HtmlOptions>();
htmlOptionsEmbed->set_HtmlFormatter(HtmlFormatter::CreateCustomFormatter(embedFontsController));
pres->Save(u"input-PFDinDisplayPro-Regular-installed.html", SaveFormat::Html, htmlOptionsEmbed);
```
 以下示例展示了如何使用 C++ 将 PowerPoint 转换为 150 DPI 高质量图像的 HTML。 
```cpp
auto pres = System::MakeObject<Presentation>(u"InputDoc.pptx");

auto htmlOpts = System::MakeObject<HtmlOptions>();
htmlOpts->set_PicturesCompression(PicturesCompression::Dpi150);

pres->Save(u"OutputDoc-dpi150.html", SaveFormat::Html, htmlOpts);
```
 以下示例展示了如何使用 C++ 将 PowerPoint 转换为全质量图像的 HTML。 
```cpp
auto pres = System::MakeObject<Presentation>(u"InputDoc.pptx");

auto htmlOpts = System::MakeObject<HtmlOptions>();
htmlOpts->set_DeletePicturesCroppedAreas(false);

pres->Save(u"Outputdoc-noCrop.html", SaveFormat::Html, htmlOpts);
```
 以下示例展示了如何使用 C++ 将 [Slide](../../slide/) 转换为 HTML。 
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
 The following example shows how to export Media files to HTML using C++. 
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

## 另见

* 枚举 [SaveFormat](../../../aspose.slides.export/saveformat/)
* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类型别名 [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [Presentation](../)
* 类 [Stream](../../../system.io/stream/)
* 类 [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* 类 [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)
* 命名空间 [Aspose::Slides](../../)
* 类库 [Aspose.Slides](../../../)