---
title: Zip64Mode
second_title: Aspose.Slides for Android via Java API Referansı
description: OpenXML dosyası için ZIP64 biçim uzantılarını ne zaman kullanacağınızı belirtir.
type: docs
url: /tr/com.aspose.slides/zip64mode/
---
**Miras:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

OpenXML dosyası için ZIP64 biçim uzantılarını ne zaman kullanacağınızı belirtir.

--------------------

OpenXML dosyası, sıkıştırılmamış dosya boyutu, sıkıştırılmış dosya boyutu ve arşivin toplam boyutu için 4 GB (2^32 bayt) sınırı ve arşivde 65.535 (2^16-1) dosya sınırı olan bir ZIP arşividir. ZIP64 biçim uzantıları bu sınırları 2^64'e yükseltir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Never](#Never) | ZIP64 biçim uzantılarını kullanmayın. |
| [IfNecessary](#IfNecessary) | Gerekirse ZIP64 biçim uzantılarını kullanın. |
| [Always](#Always) | Her zaman ZIP64 biçim uzantılarını kullanın. |
### Never {#Never}
```
public static final int Never
```


ZIP64 biçim uzantılarını kullanmayın.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```


Gerekirse ZIP64 biçim uzantılarını kullanın.

### Always {#Always}
```
public static final int Always
```


Her zaman ZIP64 biçim uzantılarını kullanın.