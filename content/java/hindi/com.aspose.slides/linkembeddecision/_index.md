---
title: LinkEmbedDecision
second_title: Aspose.Slides के लिए Java API संदर्भ
description: निर्धारित करता है कि सहेजते समय ऑब्जेक्ट कैसे प्रोसेस किया जाएगा।
type: docs
url: /hi/com.aspose.slides/linkembeddecision/
---
**विरासत:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

निर्धारित करता है कि ऑब्जेक्ट को सहेजते समय कैसे प्रोसेस किया जाएगा।
## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| [Link](#Link) | Object will be stored externally, referrenced by URL |
| [Embed](#Embed) | Object should be embedded to a generated file if possible. |
| [Ignore](#Ignore) | Object will be ignored. |
### Link {#Link}
```
public static final int Link
```

Object will be stored externally, referrenced by URL

### Embed {#Embed}
```
public static final int Embed
```

Object should be embedded to a generated file if possible. If embedding is imposible, GetUrl will be called and, depending on result, object will be referrenced by URL or ignored.

### Ignore {#Ignore}
```
public static final int Ignore
```

Object will be ignored.