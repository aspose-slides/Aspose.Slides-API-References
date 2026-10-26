---
title: LoadingStreamBehavior
second_title: Aspose.Slides Android के लिए Java API संदर्भ
description: एक मेथड को पास किया गया java.io.InputStream को एक Binary Large Object BLOB माना जाता है, देखें विवरण।
type: docs
url: /hi/com.aspose.slides/loadingstreambehavior/
---
**विरासत:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

एक मेथड को पास किया गया java.io.InputStream को एक Binary Large Object (BLOB) माना जाता है (देखें [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) विवरण)। इस एन्यूमरेशन के मान यह पहचानते हैं कि java.io.InputStream को मेथड में पास किए जाने पर कैसे संभाला जाना चाहिए। आवश्यकताओं के आधार पर सबसे कुशल व्यवहार प्रदान करने के लिए विभिन्न निर्णय लिए जा सकते हैं।

## फ़ील्ड्स

| फ़ील्ड | वर्णन |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | स्ट्रीम को अंत तक पढ़ा जाएगा और फिर रिलीज़ किया जाएगा - अर्थात। |
| [KeepLocked](#KeepLocked) | स्ट्रीम को [IPresentation](../../com.aspose.slides/ipresentation) ऑब्जेक्ट के भीतर लॉक किया जाएगा, अर्थात। |

### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

स्ट्रीम को अंत तक पढ़ा जाएगा और फिर रिलीज़ किया जाएगा - अर्थात यह सुनिश्चित किया जाएगा कि यह स्ट्रीम भविष्य में [IPresentation](../../com.aspose.slides/ipresentation) इंस्टेंस द्वारा उपयोग नहीं किया जाएगा। इसे क्लाइंट कोड द्वारा बंद किया जा सकता है या किसी अन्य तरीके से उपयोग किया जा सकता है।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // स्ट्रीम को बंद किया जा सकता है, इसे "pres" ऑब्जेक्ट के लिए अब आवश्यकता नहीं है।
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```


### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

स्ट्रीम को [IPresentation](../../com.aspose.slides/ipresentation) ऑब्जेक्ट के भीतर लॉक किया जाएगा, अर्थात स्ट्रीम की मालिकियत स्थानांतरित की जाएगी। [IPresentation](../../com.aspose.slides/ipresentation) ऑब्जेक्ट इस ऑब्जेक्ट के स्वयं डिस्पोज़ होने पर स्ट्रीम को सही तरीके से डिस्पोज़ करने के लिए जिम्मेदार होगा। यह व्यवहार अत्यंत उपयोगी है जब आपको एक बड़े BLOB फ़ाइल (जैसे बड़ा वीडियो या ऑडियो - देखें [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) विवरण) को सीरियलाइज़ करना हो और इस फ़ाइल को मेमोरी में लोड करने या अन्य प्रदर्शन संबंधी समस्याओं को रोकना हो। आप केवल इस फ़ाइल के लिए java.io.FileInputStream खोल सकते हैं और मेथड को पास कर सकते हैं, [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior चुनते हुए।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // आपको स्ट्रीम को बंद नहीं करना चाहिए या किसी अन्य तरीके से इसके साथ इंटरैक्ट नहीं करना चाहिए, यह Save मेथड में त्रुटि का कारण बनेगा।
>    // फ़ाइलस्ट्रीम को सहेजने के लिए उपयोग किया जाएगा, जिससे उच्च मेमोरी खपत रोकी जा सकेगी।
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
