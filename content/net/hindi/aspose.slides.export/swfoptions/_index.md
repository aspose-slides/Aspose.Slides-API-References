---
title: SwfOptions
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक प्रस्तुति को Swf स्वरूप में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।
type: docs
weight: 4530
url: /hi/aspose.slides.export/swfoptions/
---
## SwfOptions कक्षा

प्रस्तुति को Swf प्रारूप में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## निर्माणकर्ता

| नाम | विवरण |
| --- | --- |
| [SwfOptions](swfoptions)() | डिफ़ॉल्ट निर्माणकर्ता। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | जेनरेटेड SWF दस्तावेज़ को संकुचित किया जाना चाहिए या नहीं, यह निर्दिष्ट करता है। डिफ़ॉल्ट `true` है। |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | स्रोत फ़ॉन्ट न मिलने पर उपयोग किए जाने वाले फ़ॉन्ट को प्राप्त करता है या सेट करता है। पढ़ने-लिखने योग्य String। |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | संदर्भ मेनू को सक्षम/अक्षम करता है। डिफ़ॉल्ट `true` है। |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | ग्रेडिएंट की दृश्य शैली को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`GradientStyle`](../../aspose.slides/gradientstyle)। |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | JPEG छवियों की गुणवत्ता निर्दिष्ट करता है। डिफ़ॉल्ट 95 है। |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | छवि जो व्यूअर के शीर्ष दाएँ कोने में लोगो के रूप में प्रदर्शित होगी। छवि 32x64 पिक्सेल PNG होनी चाहिए, अन्यथा लोगो ठीक से प्रदर्शित नहीं हो सकता। |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | लोगो के लिए पूर्ण हाइपरलिंक पता प्राप्त करता है या सेट करता है। यह केवल तभी प्रभावी होता है जब [`LogoImageBytes`](./logoimagebytes) निर्दिष्ट किया गया हो। |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | प्रतिशत में सहेजने की प्रगति अद्यतन के लिए एक कॉलबैक ऑब्जेक्ट दर्शाता है। देखें [`IProgressCallback`](../../aspose.slides/iprogresscallback)। |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | निचले पैन को दिखाएं/छिपाएं। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट `true` है। |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | पूरा-स्क्रीन बटन को दिखाएं/छिपाएं। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट `true` है। |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | निर्दिष्ट करता है कि जेनरेटेड दस्तावेज़ में छिपी हुई स्लाइड्स शामिल होंगी या नहीं। डिफ़ॉल्ट `false` है। |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | बाएँ पैन को दिखाएं/छिपाएं। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट `true` है। |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | पृष्ठों के चारों ओर सीमा दिखानी चाहिए या नहीं, यह निर्दिष्ट करता है। डिफ़ॉल्ट `true` है। |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | पेज स्टेपर को दिखाएं/छिपाएं। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट `true` है। |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | खोज खंड को दिखाएं/छिपाएं। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट `true` है। |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | ऊपर के पूरे पैन को दिखाएं/छिपाएं। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट `true` है। |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | जब प्रस्तुतीकरण सहेजा जा रहा हो, तो JavaScript कॉल वाले हाइपरलिंक को छोड़ना चाहिए या नहीं, यह निर्धारित करता है। पढ़ने/लिखने योग्य Boolean। डिफ़ॉल्ट मान **false** है। |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | जब प्रस्तुतीकरण [`ISlidesLayoutOptions`](../islideslayoutoptions) को निर्यात किया जाता है, तो स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है। यह प्रॉपर्टी प्रकार [`HandoutLayoutingOptions`](../handoutlayoutingoptions) के ऑब्जेक्ट्स को असाइन करने का समर्थन नहीं करती। |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | बाएँ पैन को खुला स्थिति में प्रारंभ करें। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट `false` है। |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | निर्दिष्ट करता है कि जेनरेटेड SWF दस्तावेज़ में एकीकृत दस्तावेज़ व्यूअर शामिल होगा या नहीं। डिफ़ॉल्ट `true` है। |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | एक ऑब्जेक्ट को प्राप्त करता है या सेट करता है जो चेतावनियाँ प्राप्त करता है और निर्णय लेता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द हो जाएगी। पढ़ने/लिखने योग्य [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)। |

### उदाहरण

निम्नलिखित उदाहरण दिखाता है कि PowerPoint को SWF फ्लैश में कैसे परिवर्तित किया जाए।

```csharp
[C#]
// एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाला Presentation ऑब्जेक्ट बनाएँ
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // प्रस्तुति और नोट्स पृष्ठों को सहेज रहा है
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### देखें

* कक्षा [SaveOptions](../saveoptions)
* इंटरफ़ेस [ISwfOptions](../iswfoptions)
* नामस्थान [Aspose.Slides.Export](../../aspose.slides.export)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->