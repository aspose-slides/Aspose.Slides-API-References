---
title: TiffOptions
second_title: Aspose.Sildes for .NET API संदर्भ
description: प्रस्तुति को TIFF प्रारूप में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।
type: docs
weight: 4590
url: /hi/aspose.slides.export/tiffoptions/
---
## TiffOptions क्लास

प्रस्तुति को TIFF फ़ॉर्मेट में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [TiffOptions](tiffoptions)() | डिफ़ॉल्ट निर्माता। |

## गुण

| नाम | विवरण |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | रंग छवि को काली और सफेद छवि में परिवर्तित करने के लिए एल्गोरिद्म निर्दिष्ट करता है। यह विकल्प केवल तब लागू होगा जब [`CompressionType`](./compressiontype) को CCITT4 या CCITT3 पर सेट किया गया हो पढ़ें/लिखें [`BlackWhiteConversionMode`](../blackwhiteconversionmode)। डिफ़ॉल्ट है डिफ़ॉल्ट। |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | संकुचन प्रकार निर्दिष्ट करता है। पढ़ें/लिखें [`TiffCompressionTypes`](../tiffcompressiontypes)। |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | जब स्रोत फ़ॉन्ट नहीं मिलता है तब उपयोग किए जाने वाले फ़ॉन्ट को प्राप्त या सेट करता है। पढ़ें-लिखें String। |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | डॉट्स प्रति इंच में क्षैतिज रिज़ॉल्यूशन निर्दिष्ट करता है। पढ़ें/लिखें UInt32। |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | डॉट्स प्रति इंच में ऊर्ध्वाधर रिज़ॉल्यूशन निर्दिष्ट करता है। पढ़ें/लिखें UInt32। |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | ग्रेडिएंट की दृश्य शैली को प्राप्त या सेट करता है। पढ़ें/लिखें [`GradientStyle`](../../aspose.slides/gradientstyle)। |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | जनरेट की गई TIFF छवि का आकार निर्दिष्ट करता है। डिफ़ॉल्ट मान 0x0 है, जिसका अर्थ है कि जनरेट की गई छवि का आकार प्रस्तुति स्लाइड आकार मान के आधार पर गणना किया जाएगा। पढ़ें/लिखें Size। |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | निर्यात किए गए दस्तावेज़ में Ink ऑब्जेक्ट्स की उपस्थिति को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल पढ़ें [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | जनरेटेड छवियों के लिए पिक्सेल फ़ॉर्मेट निर्दिष्ट करता है। पढ़ें/लिखें [`ImagePixelFormat`](../imagepixelformat)। |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | प्रतिशत में सहेजने की प्रगति अपडेट के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। देखें [`IProgressCallback`](../../aspose.slides/iprogresscallback)। |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | निर्धारित करता है कि जनरेट किया गया दस्तावेज़ छिपी हुई स्लाइड्स शामिल करे या नहीं। डिफ़ॉल्ट `false` है। |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | प्रस्तुति को सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ें या नहीं, यह निर्दिष्ट करता है। पढ़ें/लिखें Boolean। डिफ़ॉल्ट मान **false** है। |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | प्रस्तुति को निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है [`ISlidesLayoutOptions`](../islideslayoutoptions)। |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | एक ऑब्जेक्ट लौटाता या सेट करता है जो चेतावनियाँ प्राप्त करता है और निर्धारित करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द होगी। पढ़ें/लिखें [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)। |

### उदाहरण

निम्न उदाहरण दिखाता है कि डिफ़ॉल्ट आकार के साथ PowerPoint को TIFF में कैसे बदलें।

```csharp
[C#]
// एक Presentation ऑब्जेक्ट को इंस्टैंटिएट करें जो एक प्रेज़ेंटेशन फ़ाइल का प्रतिनिधित्व करता है
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // प्रेज़ेंटेशन को TIFF दस्तावेज़ में सहेज रहा है
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

निम्न उदाहरण दिखाता है कि कस्टम आकार के साथ PowerPoint को TIFF में कैसे बदलें।

```csharp
[C#]
// एक Presentation ऑब्जेक्ट को इंस्टैंटिएट करें जो एक Presentation फ़ाइल का प्रतिनिधित्व करता है
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // TiffOptions क्लास को इंस्टैंटिएट करें
    TiffOptions opts = new TiffOptions();
    // कम्प्रेशन प्रकार सेट कर रहा है
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // कम्प्रेशन प्रकार
    // Default - डिफ़ॉल्ट कम्प्रेशन स्कीम (LZW) को निर्दिष्ट करता है।
    // None - कोई कम्प्रेशन नहीं दर्शाता है।
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // गहराई कम्प्रेशन प्रकार पर निर्भर करती है और इसे मैन्युअल रूप से सेट नहीं किया जा सकता।
    // रेज़ोल्यूशन यूनिट हमेशा “2” (डॉट्स प्रति इंच) के बराबर होता है
    // छवि DPI सेट कर रहा है
    opts.DpiX = 200;
    opts.DpiY = 100;
    // छवि आकार सेट करें
    opts.ImageSize = new Size(1728, 1078);
    // निर्दिष्ट छवि आकार के साथ प्रस्तुति को TIFF में सहेजें
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

निम्न उदाहरण दिखाता है कि कस्टम छवि पिक्सेल फ़ॉर्मेट के साथ PowerPoint को TIFF में कैसे बदलें।

```csharp
[C#]
// एक Presentation ऑब्जेक्ट को इंस्टैंटिएट करें जो एक Presentation फ़ाइल का प्रतिनिधित्व करता है
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat में निम्न मान होते हैं (जैसा कि दस्तावेज़ीकरण से देखा जा सकता है):
    Format1bppIndexed; // प्रति पिक्सेल 1 बिट, इंडेक्स्ड।
    Format4bppIndexed; // प्रति पिक्सेल 4 बिट, इंडेक्स्ड।
    Format8bppIndexed; // प्रति पिक्सेल 8 बिट, इंडेक्स्ड।
    Format24bppRgb; // प्रति पिक्सेल 24 बिट, RGB।
    Format32bppArgb; // प्रति पिक्सेल 32 बिट, ARGB।
    */
    // निर्दिष्ट छवि आकार के साथ प्रस्तुति को TIFF में सहेजें
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### देखें भी

* क्लास [SaveOptions](../saveoptions)
* इंटरफ़ेस [ITiffOptions](../itiffoptions)
* नेमस्पेस [Aspose.Slides.Export](../../aspose.slides.export)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->