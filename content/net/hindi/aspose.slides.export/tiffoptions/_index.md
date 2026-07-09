---
title: TiffOptions
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: विकल्प प्रदान करता है जो यह नियंत्रित करता है कि प्रस्तुति को TIFF प्रारूप में कैसे सहेजा जाता है।
type: docs
weight: 4570
url: /hi/aspose.slides.export/tiffoptions/
---
## TiffOptions क्लास

विकल्प प्रदान करता है जो नियंत्रित करते हैं कि प्रस्तुति को TIFF प्रारूप में कैसे सहेजा जाता है।

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [TiffOptions](tiffoptions)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | रंग छवि को काली और सफेद छवि में बदलने के लिए उपयोग किए जाने वाले एल्गोरिथ्म को निर्दिष्ट करता है। यह विकल्प केवल तभी लागू होगा जब [`CompressionType`](./compressiontype) को CCITT4 या CCITT3 पर सेट किया गया हो पढ़ें/लिखें [`BlackWhiteConversionMode`](../blackwhiteconversionmode)। डिफ़ॉल्ट है Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | संकुचन प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | जब स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले फ़ॉन्ट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | डॉट्स प्रति इंच में क्षैतिज रिज़ॉल्यूशन को निर्दिष्ट करता है। पढ़ें/लिखें UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | डॉट्स प्रति इंच में ऊर्ध्वाधर रिज़ॉल्यूशन को निर्दिष्ट करता है। पढ़ें/लिखें UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | ग्रेडिएंट की दृश्य शैली को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | जेनरेट किए गए TIFF छवि का आकार निर्दिष्ट करता है। डिफ़ॉल्ट मान 0x0 है, जिसका अर्थ है कि जेनरेट की गई छवि के आकार प्रस्तुति स्लाइड के आकार के आधार पर गणना किए जाएंगे। पढ़ें/लिखें Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | निर्यात किए गए दस्तावेज़ में इंक ऑब्जेक्ट्स की उपस्थिति को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल पढ़ने योग्य [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | जेनरेट किए गए चित्रों के लिए पिक्सेल फ़ॉर्मेट को निर्दिष्ट करता है। पढ़ें/लिखें [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | प्रतिशत में सहेजने की प्रगति अद्यतन के लिए एक कॉलबैक ऑब्जेक्ट को दर्शाता है। देखें [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छुपी स्लाइडें शामिल होंगी या नहीं। डिफ़ॉल्ट `false` है। |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | निर्धारित करता है कि प्रस्तुति को सहेजते समय JavaScript कॉल वाले हाइपरलिंक को छोड़ना है या नहीं। पढ़ें/लिखें Boolean। डिफ़ॉल्ट मान **false** है। |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | प्रस्तुति को निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | चेतावनियों को प्राप्त करने वाले ऑब्जेक्ट को प्राप्त करता है या सेट करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द हो जाएगी। पढ़ें/लिखें [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### उदाहरण

निम्नलिखित उदाहरण दर्शाता है कि डिफ़ॉल्ट आकार के साथ PowerPoint को TIFF में कैसे बदलें।

```csharp
[C#]
// एक Presentation ऑब्जेक्ट बनाएं जो प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // प्रेजेंटेशन को TIFF दस्तावेज़ में सहेजना
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

निम्नलिखित उदाहरण दर्शाता है कि कस्टम आकार के साथ PowerPoint को TIFF में कैसे बदलें।

```csharp
[C#]
// एक Presentation ऑब्जेक्ट बनाएं जो एक Presentation फ़ाइल का प्रतिनिधित्व करता है
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // TiffOptions क्लास का एक उदाहरण बनाएं
    TiffOptions opts = new TiffOptions();
    // संकुचन प्रकार सेट करना
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // संकुचन प्रकार
    // Default - डिफ़ॉल्ट संकुचन योजना (LZW) को निर्दिष्ट करता है।
    // None - कोई संकुचन नहीं होने को निर्दिष्ट करता है।
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // गहराई संकुचन प्रकार पर निर्भर करती है और इसे मैन्युअली सेट नहीं किया जा सकता।
    // रिज़ॉल्यूशन यूनिट हमेशा “2” के बराबर होता है (डॉट्स प्रति इंच)
    // इमेज DPI सेट करना
    opts.DpiX = 200;
    opts.DpiY = 100;
    // इमेज आकार सेट करें
    opts.ImageSize = new Size(1728, 1078);
    // निर्दिष्ट इमेज आकार के साथ प्रेजेंटेशन को TIFF में सहेजें
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

निम्नलिखित उदाहरण दर्शाता है कि कस्टम छवि पिक्सेल फ़ॉर्मेट के साथ PowerPoint को TIFF में कैसे बदलें।

```csharp
[C#]
// एक Presentation ऑब्जेक्ट बनाएं जो एक Presentation फ़ाइल का प्रतिनिधित्व करता है
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat में निम्नलिखित मान होते हैं (जैसा कि दस्तावेज़ीकरण से देखा जा सकता है):
    Format1bppIndexed; // 1 बिट प्रति पिक्सेल, इंडेक्स्ड।
    Format4bppIndexed; // 4 बिट प्रति पिक्सेल, इंडेक्स्ड।
    Format8bppIndexed; // 8 बिट प्रति पिक्सेल, इंडेक्स्ड।
    Format24bppRgb; // 24 बिट प्रति पिक्सेल, RGB।
    Format32bppArgb; // 32 बिट प्रति पिक्सेल, ARGB।
    */
    // निर्दिष्ट इमेज आकार के साथ प्रेजेंटेशन को TIFF में सहेजें
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### देखें

* क्लास [SaveOptions](../saveoptions)
* इंटरफ़ेस [ITiffOptions](../itiffoptions)
* नामस्थान [Aspose.Slides.Export](../../aspose.slides.export)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->