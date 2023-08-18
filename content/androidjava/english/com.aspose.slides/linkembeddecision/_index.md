---
title: LinkEmbedDecision
second_title: Aspose.Slides for Android via Java API Reference
description: Determines how object will be processed during saving.
type: docs
weight: 289
url: /com.aspose.slides/linkembeddecision/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Determines how object will be processed during saving.
## Fields

| Field | Description |
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

