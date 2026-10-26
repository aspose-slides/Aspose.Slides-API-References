---
title: LinkEmbedDecision
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: निर्धारित करता है कि सहेजने के दौरान ऑब्जेक्ट कैसे प्रोसेस किया जाएगा।
type: docs
url: /hi/com.aspose.slides/linkembeddecision/
---
**विरासत:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

ऑब्जेक्ट को सहेजते समय कैसे प्रोसेस किया जाएगा, यह निर्धारित करता है।
## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| [Link](#Link) | ऑब्जेक्ट को बाहरी रूप से संग्रहीत किया जाएगा, URL द्वारा संदर्भित |
| [Embed](#Embed) | ऑब्जेक्ट को संभव होने पर उत्पन्न फाइल में एम्बेड किया जाना चाहिए। |
| [Ignore](#Ignore) | ऑब्जेक्ट को अनदेखा किया जाएगा। |
### लिंक {#Link}
```
public static final int Link
```

ऑब्जेक्ट को बाहरी रूप से संग्रहीत किया जाएगा, URL द्वारा संदर्भित

### एंबेड {#Embed}
```
public static final int Embed
```

ऑब्जेक्ट को संभव होने पर उत्पन्न फाइल में एम्बेड किया जाना चाहिए। यदि एम्बेड करना असम्भव है, तो GetUrl को कॉल किया जाएगा और परिणाम के आधार पर, ऑब्जेक्ट को URL द्वारा संदर्भित या अनदेखा किया जाएगा।

### अनदेखा {#Ignore}
```
public static final int Ignore
```

ऑब्जेक्ट को अनदेखा किया जाएगा।