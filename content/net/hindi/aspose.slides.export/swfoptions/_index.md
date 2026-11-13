---
title: SwfOptions
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक प्रस्तुति को Swf फ़ॉर्मेट में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।
type: docs
weight: 4550
url: /hi/aspose.slides.export/swfoptions/
---
## SwfOptions क्लास

एक प्रेजेंटेशन को Swf फ़ॉर्मेट में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [SwfOptions](swfoptions)() | डिफ़ॉल्ट निर्माता। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | निर्धारित करता है कि उत्पन्न SWF दस्तावेज़ संकुचित होना चाहिए या नहीं। डिफ़ॉल्ट `true` है। |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | जब स्रोत फ़ॉन्ट नहीं मिलता है तो उपयोग किया जाने वाला फ़ॉन्ट लौटाता या सेट करता है। पढ़ने/लिखने योग्य स्ट्रिंग। |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | संदर्भ मेनू सक्षम/अक्षम करता है। डिफ़ॉल्ट true है। |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | ग्रेडिएंट की दृश्य शैली लौटाता या सेट करता है। पढ़ने/लिखने योग्य [`GradientStyle`](../../aspose.slides/gradientstyle)। |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | JPEG चित्रों की गुणवत्ता निर्धारित करता है। डिफ़ॉल्ट 95 है। |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | छवि जो व्यूअर के ऊपर दाएँ कोने में लोगो के रूप में प्रदर्शित होगी। छवि 32x64 पिक्सेल PNG होनी चाहिए, अन्यथा लोगो गलत तरीके से दिख सकता है। |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | लोगो के लिए पूर्ण हाइपरलिंक पता प्राप्त करता या सेट करता है। यह केवल तब प्रभावी होता है जब [`LogoImageBytes`](./logoimagebytes) निर्दिष्ट किया गया हो। |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | प्रतिशत में सहेजने की प्रगति अपडेट के लिए एक कॉलबैक ऑब्जेक्ट दर्शाता है। देखें [`IProgressCallback`](../../aspose.slides/iprogresscallback)। |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | निचला पेन दिखाएं/छिपाएं। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | फ़ुलस्क्रीन बटन दिखाएं/छिपाएं। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी हुई स्लाइड्स शामिल होनी चाहिए या नहीं। डिफ़ॉल्ट `false` है। |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | बायाँ पेन दिखाएं/छिपाएं। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | निर्धारित करता है कि पृष्ठों के चारों ओर बॉर्डर दिखाया जाना चाहिए या नहीं। डिफ़ॉल्ट true है। |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | पेज स्टैपर दिखाएं/छिपाएं। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | खोज सेक्शन दिखाएं/छिपाएं। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | पूरे शीर्ष पेन को दिखाएं/छिपाएं। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | प्रेजेंटेशन सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ना है या नहीं, यह निर्धारित करता है। पढ़ने/लिखने योग्य बूलियन। डिफ़ॉल्ट मान **false** है। |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | प्रेजेंटेशन [`ISlidesLayoutOptions`](../islideslayoutoptions) निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता या सेट करता है। यह प्रॉपर्टी [`HandoutLayoutingOptions`](../handoutlayoutingoptions) प्रकार के ऑब्जेक्ट को असाइन करने का समर्थन नहीं करती। |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | बायाँ पेन खुला स्थिति में शुरू करें। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट false है। |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | निर्धारित करता है कि उत्पन्न SWF दस्तावेज़ में एकीकृत दस्तावेज़ व्यूअर शामिल होना चाहिए या नहीं। डिफ़ॉल्ट `true` है। |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | चेतावनियों को प्राप्त करने वाले और यह निर्णय लेने वाले ऑब्जेक्ट को लौटाता या सेट करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द हो जाएगी। पढ़ने/लिखने योग्य [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)। |

### उदाहरण

निम्न उदाहरण दिखाता है कि PowerPoint को SWF Flash में कैसे परिवर्तित किया जाए।

```csharp
[C#]
// एक Presentation ऑब्जेक्ट को इनस्टैंटियेट करता है जो एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // प्रेजेंटेशन और नोट्स पृष्ठों को सहेजना
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### देखें भी

* क्लास [SaveOptions](../saveoptions)
* इंटरफ़ेस [ISwfOptions](../iswfoptions)
* नेमस्पेस [Aspose.Slides.Export](../../aspose.slides.export)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->