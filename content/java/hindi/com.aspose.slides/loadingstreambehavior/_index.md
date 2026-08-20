---
title: LoadingStreamBehavior
second_title: Aspose.Slides for Java API संदर्भ
description: एक विधि को पास किया गया java.io.InputStream को बाइनरी लैज ऑब्जेक्ट BLOB माना जाता है, विवरण देखें।
type: docs
url: /hi/com.aspose.slides/loadingstreambehavior/
---
**विरासत:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

विधि को पास किया गया java.io.InputStream को बाइनरी बड़े वस्तु (BLOB) के रूप में माना जाता है ([IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) विवरण देखें)। इस एन्‍यूमरेशन के मान यह पहचानते हैं कि java.io.InputStream को विधि को पास किए जाने पर कैसे व्यवहार करना चाहिए। आवश्यकताओं के आधार पर, सबसे कुशल व्यवहार प्रदान करने के लिए विभिन्न निर्णय लिये जा सकते हैं।

## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | स्ट्रीम को अंत तक पढ़ा जाएगा और फिर रिलीज़ किया जाएगा - अर्थात |
| [KeepLocked](#KeepLocked) | स्ट्रीम को [IPresentation](../../com.aspose.slides/ipresentation) ऑब्जेक्ट के भीतर लॉक किया जाएगा, अर्थात |

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
>    fileStream.close(); // स्ट्रीम को बंद किया जा सकता है, यह "pres" ऑब्जेक्ट के लिए अब आवश्यक नहीं है।
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

स्ट्रीम को [IPresentation](../../com.aspose.slides/ipresentation) ऑब्जेक्ट के भीतर लॉक किया जाएगा, अर्थात स्ट्रीम का स्वामित्व स्थानांतरित हो जाएगा। [IPresentation](../../com.aspose.slides/ipresentation) ऑब्जेक्ट इस ऑब्जेक्ट के स्वयं डिस्पोज़ होने पर स्ट्रीम को सही ढंग से डिस्पोज़ करने के लिए जिम्मेदार होगा। यह व्यवहार अत्यंत उपयोगी है जब आपको बड़े BLOB फ़ाइल (जैसे बड़ा वीडियो या ऑडियो - [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) विवरण देखें) को सीरियलाइज़ करने की आवश्यकता होती है और आप इस फ़ाइल को मेमोरी में लोड होने या अन्य प्रदर्शन समस्याओं से बचना चाहते हैं। आप बस इस फ़ाइल के लिए java.io.FileInputStream खोल सकते हैं और किसी विधि को पास कर सकते हैं, [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior चुनें।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // आपको स्ट्रीम को बंद नहीं करना चाहिए या उसे किसी अन्य तरीके से उपयोग नहीं करना चाहिए, यह Save मेथड में त्रुटि का कारण बनेगा।
>    // फ़ाइलस्ट्रीम को सहेजने के लिए उपयोग किया जाएगा, जो उच्च मेमोरी उपयोग को रोकता है।
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```