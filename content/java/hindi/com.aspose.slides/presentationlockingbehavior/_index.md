---
title: PresentationLockingBehavior
second_title: Aspose.Slides for Java API संदर्भ
description: लोड करते समय और किसी उदाहरण के साथ काम करते समय स्रोत फ़ाइल या java.io.InputStream को संभालने से संबंधित व्यवहार का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/presentationlockingbehavior/
---
**विरासत:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum  
```
public final class PresentationLockingBehavior extends System.Enum
```

[IPresentation](../../com.aspose.slides/ipresentation) स्रोत (फ़ाइल या java.io.InputStream) को लोड करने और [IPresentation](../../com.aspose.slides/ipresentation) के एक उदाहरण के साथ काम करते समय व्यवहार का प्रतिनिधित्व करता है।

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

स्रोत वह पैरामीटर है जो [IPresentation](../../com.aspose.slides/ipresentation) कंस्ट्रक्टर को पास किया जाता है। नीचे दिए गए उदाहरण में, स्रोत "pres.pptx" फ़ाइल है: इस उदाहरण के लिए, स्रोत ("pres.pptx" फ़ाइल) [IPresentation](../../com.aspose.slides/ipresentation) इंस्टेंस जीवनकाल के लिए लॉक किया जाएगा, अर्थात् इसे अन्य प्रक्रिया द्वारा बदला या हटाया नहीं जा सकता।

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | स्रोत केवल [IPresentation](../../com.aspose.slides/ipresentation) कंस्ट्रक्टर के निष्पादन के समय के लिए लॉक किया जाएगा। |
| [KeepLocked](#KeepLocked) | स्रोत [IPresentation](../../com.aspose.slides/ipresentation) इंस्टेंस के पूरे जीवनकाल के लिए लॉक किया जाएगा, जब तक इसे नष्ट नहीं किया जाता। |

### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

स्रोत केवल [IPresentation](../../com.aspose.slides/ipresentation) कंस्ट्रक्टर के निष्पादन के समय के लिए लॉक किया जाएगा।

--------------------

यदि ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) को false सेट किया जाता है, तो सभी BLOBs मेमोरी में लोड हो जाएंगे। अन्यथा, अस्थायी फ़ाइलों जैसी अन्य विधियों का उपयोग किया जा सकता है।

--------------------

यह व्यवहार [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) की तुलना में धीमा है, और यदि स्रोत का स्वामित्व [IPresentation](../../com.aspose.slides/ipresentation) को पास करना संभव है, तो [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) का उपयोग करने की सिफारिश की जाती है।

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

स्रोत [IPresentation](../../com.aspose.slides/ipresentation) इंस्टेंस के पूरे जीवनकाल के लिए लॉक किया जाएगा, जब तक इसे नष्ट नहीं किया जाता।

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) को इस व्यवहार को उपयोग करने के लिए true सेट होना आवश्यक है, अन्यथा अपवाद फेंका जाएगा।

--------------------

यह व्यवहार अनुशंसित है, यह तेज़ है और [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease) की तुलना में कम मेमोरी का उपयोग करता है।