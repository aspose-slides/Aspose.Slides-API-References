---
title: SwfOptions
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक प्रस्तुति को Swf प्रारूप में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।
type: docs
weight: 4530
url: /hi/aspose.slides.export/swfoptions/
---
## SwfOptions क्लास

प्रेजेंटेशन को Swf फ़ॉर्मेट में सहेजा जाने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## निर्माणकर्ता

| नाम | विवरण |
| --- | --- |
| [SwfOptions](swfoptions)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | निर्धारित करता है कि उत्पन्न SWF दस्तावेज़ को संकुचित किया जाना चाहिए या नहीं। डिफ़ॉल्ट `true` है। |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | स्रोत फ़ॉन्ट न मिलने की स्थिति में उपयोग किए जाने वाले फ़ॉन्ट को प्राप्त करता या सेट करता है। पठनीय-लेखनीय String। |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | कॉन्टेक्स्ट मेनू को सक्षम/अक्षम करता है। डिफ़ॉल्ट true है। |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | ग्रेडिएंट की दृश्य शैली को प्राप्त करता या सेट करता है। पठनीय-लेखनीय [`GradientStyle`](../../aspose.slides/gradientstyle)। |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | JPEG छवियों की गुणवत्ता को निर्धारित करता है। डिफ़ॉल्ट 95 है। |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | व्यूअर के ऊपर दाएँ कोने में लोगो के रूप में दिखाने वाली छवि। छवि 32x64 पिक्सेल PNG होनी चाहिए, अन्यथा लोगो गलत तरीके से प्रदर्शित हो सकता है। |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | लोगो के लिए पूर्ण हाइपरलिंक पता प्राप्त करता या सेट करता है। यह केवल तभी प्रभावी होता है जब [`LogoImageBytes`](./logoimagebytes) निर्दिष्ट किया गया हो। |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | प्रत्येक प्रतिशत में सहेजने की प्रगति अपडेट के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। देखें [`IProgressCallback`](../../aspose.slides/iprogresscallback)। |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | नीचे पेन को दिखाएँ/छिपाएँ। flashvars में इसे ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | फुलस्क्रीन बटन को दिखाएँ/छिपाएँ। flashvars में इसे ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल की जानी चाहिए या नहीं। डिफ़ॉल्ट `false` है। |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | बाएँ पेन को दिखाएँ/छिपाएँ। flashvars में इसे ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | पृष्ठों के चारों ओर बॉर्डर दिखाया जाना चाहिए या नहीं, यह निर्धारित करता है। डिफ़ॉल्ट true है। |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | पेज स्टेपर को दिखाएँ/छिपाएँ। flashvars में इसे ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | खोज अनुभाग को दिखाएँ/छिपाएँ। flashvars में इसे ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | पूरा शीर्ष पेन दिखाएँ/छिपाएँ। flashvars में इसे ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | प्रेजेंटेशन सहेजते समय JavaScript कॉल वाले हाइपरलिंक को छोड़ना चाहिए या नहीं, यह निर्धारित करता है। पठनीय-लेखनीय Boolean। डिफ़ॉल्ट मान **false** है। |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | प्रेजेंटेशन [`ISlidesLayoutOptions`](../islideslayoutoptions) निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता या सेट करता है। यह प्रॉपर्टी प्रकार [`HandoutLayoutingOptions`](../handoutlayoutingoptions) के ऑब्जेक्ट को असाइन करने का समर्थन नहीं करती। |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | बाएँ पेन खुले स्थिति से शुरू करें। flashvars में इसे ओवरराइड किया जा सकता है। डिफ़ॉल्ट false है। |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | निर्धारित करता है कि उत्पन्न SWF दस्तावेज़ में एकीकृत दस्तावेज़ व्यूअर शामिल होना चाहिए या नहीं। डिफ़ॉल्ट `true` है। |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | एक ऑब्जेक्ट लौटाता या सेट करता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द कर दी जाएगी। पठनीय-लेखनीय [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)। |

### उदाहरण

निम्नलिखित उदाहरण दिखाता है कि PowerPoint को SWF Flash में कैसे बदलें।

```csharp
[C#]
// एक Presentation ऑब्जेक्ट बनाएं जो एक प्रस्तुति फ़ाइल को दर्शाता है
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // प्रेजेंटेशन और नोट्स पृष्ठों को सहेज रहा है
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### देखें

* क्लास [SaveOptions](../saveoptions)
* इंटरफ़ेस [ISwfOptions](../iswfoptions)
* नामस्थान [Aspose.Slides.Export](../../aspose.slides.export)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->