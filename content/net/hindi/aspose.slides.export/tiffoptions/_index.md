---
title: TiffOptions
second_title: Aspose.Sildes for .NET API संदर्भ
description: विकल्प प्रदान करता है जो निर्धारित करता है कि प्रेजेंटेशन को TIFF फ़ॉर्मेट में कैसे सहेजा जाए।
type: docs
weight: 4570
url: /hi/aspose.slides.export/tiffoptions/
---
## TiffOptions वर्ग

प्रेजेंटेशन को TIFF फ़ॉर्मेट में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [TiffOptions](tiffoptions)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | रंग छवि को काली और सफेद छवि में परिवर्तित करने के लिए एल्गोरिद्म निर्दिष्ट करता है। यह विकल्प केवल तभी लागू होगा जब [`CompressionType`](./compressiontype) को CCITT4 या CCITT3 पर सेट किया गया हो पढ़ें/लिखें [`BlackWhiteConversionMode`](../blackwhiteconversionmode)। डिफ़ॉल्ट है Default। |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | संपीड़न प्रकार निर्दिष्ट करता है। पढ़ें/लिखें [`TiffCompressionTypes`](../tiffcompressiontypes)। |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | स्रोत फ़ॉन्ट न मिलने पर उपयोग में लाया गया फ़ॉन्ट लौटाता या सेट करता है। पढ़ें/लिखें String। |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | क्षैतिज रेज़ोल्यूशन (डॉट्स प्रति इंच) निर्दिष्ट करता है। पढ़ें/लिखें UInt32। |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | ऊर्ध्वाधर रेज़ोल्यूशन (डॉट्स प्रति इंच) निर्दिष्ट करता है। पढ़ें/लिखें UInt32। |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | ग्रेडिएंट की दृश्य शैली लौटाता या सेट करता है। पढ़ें/लिखें [`GradientStyle`](../../aspose.slides/gradientstyle)। |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | उत्पन्न TIFF छवि का आकार निर्दिष्ट करता है। डिफ़ॉल्ट मान 0x0 है, जिसका अर्थ है कि उत्पन्न छवि आकार प्रेजेंटेशन स्लाइड आकार के आधार पर गणना किया जाएगा। पढ़ें/लिखें Size। |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | निर्यातित दस्तावेज़ में Ink ऑब्जेक्ट्स के रूप को नियंत्रित करने के विकल्प प्रदान करता है। केवल पढ़ने योग्य [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | उत्पन्न छवियों के लिये पिक्सेल फ़ॉर्मेट निर्दिष्ट करता है। पढ़ें/लिखें [`ImagePixelFormat`](../imagepixelformat)। |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | प्रतिशत में सहेजने की प्रगति अपडेट के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। देखें [`IProgressCallback`](../../aspose.slides/iprogresscallback)। |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। डिफ़ॉल्ट है `false`। |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | प्रेजेंटेशन सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ने का निर्धारण करता है। पढ़ें/लिखें Boolean। डिफ़ॉल्ट मान **false** है। |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | प्रेजेंटेशन निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त या सेट करता है [`ISlidesLayoutOptions`](../islideslayoutoptions)। |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | उन चेतावनियों को प्राप्त करने वाले ऑब्जेक्ट को लौटाता या सेट करता है जो निर्धारित करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द की जाएगी। पढ़ें/लिखें [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)। |

### उदाहरण

निम्न उदाहरण डिफ़ॉल्ट आकार के साथ PowerPoint को TIFF में परिवर्तित करने का तरीका दर्शाता है।

```csharp
[C#]
// एक Presentation ऑब्जेक्ट बनाएं जो एक प्रेजेंटेशन फ़ाइल का प्रतिनिधित्व करता है
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // प्रेजेंटेशन को TIFF दस्तावेज़ में सहेजना
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

निम्न उदाहरण कस्टम आकार के साथ PowerPoint को TIFF में परिवर्तित करने का तरीका दर्शाता है।

```csharp
[C#]
// एक Presentation ऑब्जेक्ट बनाएं जो एक Presentation फ़ाइल का प्रतिनिधित्व करता है
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // TiffOptions वर्ग का एक उदाहरण बनाएं
    TiffOptions opts = new TiffOptions();
    // संपीड़न प्रकार सेट करना
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // संपीड़न प्रकार
    // Default - डिफ़ॉल्ट संपीड़न योजना (LZW) निर्दिष्ट करता है।
    // None - कोई संपीड़न नहीं होने को निर्दिष्ट करता है।
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // गहराई संपीड़न प्रकार पर निर्भर करती है और इसे मैन्युअल रूप से सेट नहीं किया जा सकता।
    // रिज़ॉल्यूशन इकाई हमेशा “2” (डॉट्स प्रति इंच) के बराबर होती है
    // इमेज DPI सेट करना
    opts.DpiX = 200;
    opts.DpiY = 100;
    // इमेज आकार सेट करें
    opts.ImageSize = new Size(1728, 1078);
    // निर्दिष्ट इमेज आकार के साथ प्रेजेंटेशन को TIFF में सहेजें
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

निम्न उदाहरण कस्टम छवि पिक्सेल फ़ॉर्मेट के साथ PowerPoint को TIFF में परिवर्तित करने का तरीका दर्शाता है।

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

### संबंधित देखें

* वर्ग [SaveOptions](../saveoptions)
* इंटरफ़ेस [ITiffOptions](../itiffoptions)
* नेमस्पेस [Aspose.Slides.Export](../../aspose.slides.export)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->