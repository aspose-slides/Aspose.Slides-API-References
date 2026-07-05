---
title: GetImage
second_title: Aspose.Sildes for .NET API संदर्भ
description: कस्टम स्केलिंग के साथ एक थंबनेल इमेज ऑब्जेक्ट लौटाता है।
type: docs
weight: 80
url: /hi/aspose.slides/slide/getimage/
---
## GetImage(float, float) {#getimage_5}

कस्टम स्केलिंग के साथ एक थंबनेल इमेज ऑब्जेक्ट लौटाता है।

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scaleX | Single | x-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |
| scaleY | Single | y-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |

### रिटर्न वैल्यू

IImage ऑब्जेक्ट।

### उदाहरण

निम्नलिखित उदाहरण दिखाता है कि PowerPoint प्रेज़ेंटेशन से थंबनेल कैसे जेनरेट करें।

```csharp
[C#]
// एक Presentation क्लास को बनाता है जो प्रस्तुति फ़ाइल का प्रतिनिधित्व करती है
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // पहली स्लाइड तक पहुँचें
    ISlide sld = pres.Slides[0];
    // पूरा स्केल वाला इमेज बनाएँ
    IImage bmp = sld.GetImage(1f, 1f);
    // इमेज को डिस्क में JPEG फ़ॉर्मेट में सहेजें
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

निम्नलिखित उदाहरण दिखाता है कि स्लाइड्स को बिटमैप में कैसे कनवर्ट करें और PNG में इमेजेस को सहेजें।

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // प्रेज़ेंटेशन की पहली स्लाइड को एक Bitmap ऑब्जेक्ट में बदलता है
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // इमेज को PNG फ़ॉर्मेट में सहेजता है
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

निम्नलिखित उदाहरण दिखाता है कि PowerPoint PPT/PPTX को JPG में कैसे कनवर्ट करें।

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// पूर्ण स्केल इमेज बनाता है
		IImage bmp = sld.GetImage(1f, 1f);
		// इमेज को डिस्क में JPEG फ़ॉर्मेट में सहेजें
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

निम्नलिखित उदाहरण दिखाता है कि कस्टमाइज़्ड डायमेंशन के साथ PowerPoint PPT/PPTX को JPG में कैसे कनवर्ट करें।

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// आयाम निर्धारित करें
	int desiredX = 1200;
	int desiredY = 800;
	// X और Y के स्केल किए गए मान प्राप्त करें
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// पूर्ण स्केल इमेज बनाता है
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// इमेज को डिस्क में JPEG फ़ॉर्मेट में सहेजें
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### और देखें

* इंटरफ़ेस [IImage](../../iimage)
* क्लास [Slide](../../slide)
* नेमस्पेस [Aspose.Slides](../../slide)
* असेंबली [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

एक थंबनेल इमेज ऑब्जेक्ट लौटाता है (वास्तविक आकार का 20%).

```csharp
public IImage GetImage()
```

### और देखें

* इंटरफ़ेस [IImage](../../iimage)
* क्लास [Slide](../../slide)
* नेमस्पेस [Aspose.Slides](../../slide)
* असेंबली [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

निर्दिष्ट आकार के साथ एक थंबनेल इमेज ऑब्जेक्ट लौटाता है।

```csharp
public IImage GetImage(Size imageSize)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageSize | Size | बनाने के लिए इमेज का आकार। |

### रिटर्न वैल्यू

Image ऑब्जेक्ट।

### उदाहरण

निम्नलिखित उदाहरण दिखाता है कि C# का उपयोग करके कस्टम आकार के साथ स्लाइड्स को इमेजेज़ में कैसे कनवर्ट करें।

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // प्रेज़ेंटेशन की पहली स्लाइड को निर्दिष्ट आकार के साथ एक Bitmap में बदलता है
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // इमेज को JPEG फ़ॉर्मेट में सहेजता है
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### और देखें

* इंटरफ़ेस [IImage](../../iimage)
* क्लास [Slide](../../slide)
* नेमस्पेस [Aspose.Slides](../../slide)
* असेंबली [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

निर्दिष्ट पैरामीटर के साथ एक थंबनेल टिफ इमेज ऑब्जेक्ट लौटाता है।

```csharp
public IImage GetImage(ITiffOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | ITiffOptions | टिफ विकल्प। |

### रिटर्न वैल्यू

Image ऑब्जेक्ट।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| InvalidOperationException | जब options.SlideLayoutOption NotesCommentsLayoutingOptions हो और उसकी प्रॉपर्टी NotesPosition का मान NotesPositions.BottomFull हो तो थ्रो किया जाता है। |

### और देखें

* इंटरफ़ेस [IImage](../../iimage)
* इंटरफ़ेस [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* क्लास [Slide](../../slide)
* नेमस्पेस [Aspose.Slides](../../slide)
* असेंबली [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

एक थंबनेल इमेज ऑब्जेक्ट लौटाता है।

```csharp
public IImage GetImage(IRenderingOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | IRenderingOptions | रेंडरिंग विकल्प। |

### रिटर्न वैल्यू

Image ऑब्जेक्ट।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| InvalidOperationException | जब notesCommentsLayouting.NotesPosition का मान NotesPositions.BottomFull हो तब थ्रो किया जाता है। |

### और देखें

* इंटरफ़ेस [IImage](../../iimage)
* इंटरफ़ेस [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* क्लास [Slide](../../slide)
* नेमस्पेस [Aspose.Slides](../../slide)
* असेंबली [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

कस्टम स्केलिंग के साथ एक थंबनेल इमेज ऑब्जेक्ट लौटाता है।

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | IRenderingOptions | रेंडरिंग विकल्प। |
| scaleX | Single | x-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |
| scaleY | Single | y-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |

### रिटर्न वैल्यू

Bitmap ऑब्जेक्ट्स।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| InvalidOperationException | जब notesCommentsLayouting.NotesPosition का मान NotesPositions.BottomFull हो तब थ्रो किया जाता है। |

### उदाहरण

निम्नलिखित उदाहरण दिखाता है कि C# का उपयोग करके नोट्स और कमेंट्स वाले स्लाइड्स को इमेजेज़ में कैसे कनवर्ट करें।

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // रेंडरिंग विकल्प बनाएं
    IRenderingOptions options = new RenderingOptions();
    // नोट्स और कमेंट्स लेआउटिंग विकल्प बनाएं
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // पेज पर नोट्स की स्थिति निर्धारित करता है
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // पेज पर कमेंट्स की स्थिति निर्धारित करता है
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // कमेंट आउटपुट क्षेत्र की चौड़ाई सेट करता है
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // कमेंट्स क्षेत्र के लिए रंग सेट करता है
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // रेंडरिंग के लिए लेआउट विकल्प सेट करें
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // प्रेज़ेंटेशन की पहली स्लाइड को IImage ऑब्जेक्ट में बदलता है
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // इमेज को GIF फ़ॉर्मेट में सहेजता है
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### और देखें

* इंटरफ़ेस [IImage](../../iimage)
* इंटरफ़ेस [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* क्लास [Slide](../../slide)
* नेमस्पेस [Aspose.Slides](../../slide)
* असेंबली [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

निर्दिष्ट आकार के साथ एक थंबनेल इमेज ऑब्जेक्ट लौटाता है।

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | IRenderingOptions | रेंडरिंग विकल्प। |
| imageSize | Size | बनाने के लिए इमेज का आकार। |

### रिटर्न वैल्यू

Image ऑब्जेक्ट।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| InvalidOperationException | जब options.SlideLayoutOption NotesCommentsLayoutingOptions हो और उसकी प्रॉपर्टी NotesPosition का मान NotesPositions.BottomFull हो तो थ्रो किया जाता है। |

### और देखें

* इंटरफ़ेस [IImage](../../iimage)
* इंटरफ़ेस [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* क्लास [Slide](../../slide)
* नेमस्पेस [Aspose.Slides](../../slide)
* असेंबली [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->