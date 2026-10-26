---
title: ResourceLoadingAction
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: बाहरी संसाधन लोडिंग की अवस्था को निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/resourceloadingaction/
---
**वंशजता:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

बाहरी संसाधन लोडिंग की अवस्था को निर्दिष्ट करता है।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [Default](#Default) | Aspose.Slides बाहरी संसाधन को सामान्य रूप से लोड करेगा। |
| [Skip](#Skip) | Aspose.Slides बाहरी संसाधन को लोड करने को छोड़ देगा। |
| [UserProvided](#UserProvided) | Aspose.Slides उपयोगकर्ता द्वारा [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) में प्रदान किए गए बाइट ऐरे का उपयोग इमेज डेटा के रूप में करेगा। |
### Default {#Default}
```
public static final int Default
```

Aspose.Slides बाहरी संसाधन को सामान्य रूप से लोड करेगा।

### Skip {#Skip}
```
public static final int Skip
```

Aspose.Slides बाहरी संसाधन को लोड करने को छोड़ देगा। केवल लिंक बिना डेटा के एक छवि के लिए संग्रहीत किया जाएगा।

### UserProvided {#UserProvided}
```
public static final int UserProvided
```

Aspose.Slides उपयोगकर्ता द्वारा [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) में प्रदान किए गए बाइट ऐरे का उपयोग इमेज डेटा के रूप में करेगा।