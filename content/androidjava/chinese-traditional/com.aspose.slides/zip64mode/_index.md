---
title: Zip64Mode
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 指定何時在 OpenXML 檔案中使用 ZIP64 格式擴充功能。
type: docs
url: /zh-hant/com.aspose.slides/zip64mode/
---
**繼承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

指定何時在 OpenXML 檔案中使用 ZIP64 格式擴充功能。

--------------------

OpenXML 檔案是一個 ZIP 壓縮檔，其未壓縮檔案大小、壓縮後檔案大小以及整個壓縮檔的總大小皆有限制為 4 GB（2^32 位元組），且壓縮檔中檔案數量上限為 65,535（2^16-1）個。ZIP64 格式擴充功能將這些限制提升至 2^64。

## 欄位

| 欄位 | 描述 |
| --- | --- |
| [Never](#Never) | 不要使用 ZIP64 格式擴充功能。 |
| [IfNecessary](#IfNecessary) | 在需要時使用 ZIP64 格式擴充功能。 |
| [Always](#Always) | 始終使用 ZIP64 格式擴充功能。 |
### Never {#Never}
```
public static final int Never
```

不要使用 ZIP64 格式擴充功能。

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```

在需要時使用 ZIP64 格式擴充功能。

### Always {#Always}
```
public static final int Always
```

始終使用 ZIP64 格式擴充功能。