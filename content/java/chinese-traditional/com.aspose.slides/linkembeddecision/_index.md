---
title: LinkEmbedDecision
second_title: Aspose.Slides for Java API 參考
description: 決定物件在儲存過程中的處理方式。
type: docs
url: /zh-hant/com.aspose.slides/linkembeddecision/
---
**繼承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

決定物件在儲存過程中的處理方式。
## 欄位

| 欄位 | 描述 |
| --- | --- |
| [Link](#Link) | 物件將以 URL 方式外部儲存，並以 URL 參照。 |
| [Embed](#Embed) | 如果可能，物件應該嵌入生成的檔案中。 |
| [Ignore](#Ignore) | 物件將被忽略。 |
### 連結 {#Link}
```
public static final int Link
```

物件將以 URL 方式外部儲存，並以 URL 參照。

### 嵌入 {#Embed}
```
public static final int Embed
```

如果可能，物件應嵌入生成的檔案中。如果嵌入不可能，將呼叫 GetUrl，根據結果，物件將以 URL 參照或被忽略。

### 忽略 {#Ignore}
```
public static final int Ignore
```

物件將被忽略。