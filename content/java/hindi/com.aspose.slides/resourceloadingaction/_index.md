---
title: ResourceLoadingAction
second_title: Aspose.Slides के लिए Java API संदर्भ
description: बाहरी संसाधन लोडिंग के मोड को निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/resourceloadingaction/
---
**विरासत:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

बाहरी संसाधन लोडिंग के मोड को निर्दिष्ट करता है।

## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| [Default](#Default) | Aspose.Slides सामान्यतः बाहरी संसाधन लोड करेगा। |
| [Skip](#Skip) | Aspose.Slides बाहरी संसाधन का लोडिंग छोड़ देगा। |
| [UserProvided](#UserProvided) | Aspose.Slides उपयोगकर्ता द्वारा प्रदान किए गए बाइट एरे को [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) को इमेज डेटा के रूप में उपयोग करेगा। |

### Default {#Default}
```
public static final int Default
```

Aspose.Slides सामान्यतः बाहरी संसाधन लोड करेगा।

### Skip {#Skip}
```
public static final int Skip
```

Aspose.Slides बाहरी संसाधन का लोडिंग छोड़ देगा। केवल डेटा के बिना लिंक को छवि के लिए संग्रहीत किया जाएगा।

### UserProvided {#UserProvided}
```
public static final int UserProvided
```

Aspose.Slides उपयोगकर्ता द्वारा प्रदान किए गए बाइट एरे को [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) को इमेज डेटा के रूप में उपयोग करेगा।