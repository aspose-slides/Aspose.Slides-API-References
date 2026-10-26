---
title: Zip64Mode
second_title: Aspose.Slides for Java API Referansı
description: OpenXML dosyası için ZIP64 format uzantılarının ne zaman kullanılacağını belirtir.
type: docs
url: /tr/com.aspose.slides/zip64mode/
---
**Kalıtım:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

OpenXML dosyası için ZIP64 format uzantılarının ne zaman kullanılacağını belirtir.

--------------------

OpenXML dosyası, sıkıştırılmamış dosya boyutu, sıkıştırılmış dosya boyutu ve arşivin toplam boyutu için 4 GB (2^32 bayt) sınırlaması ve arşivde 65.535 (2^16-1) dosya sınırlaması bulunan bir ZIP arşividir. ZIP64 format uzantıları bu sınırlamaları 2^64’e yükseltir.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Never](#Never) | ZIP64 format uzantılarını kullanmayın. |
| [IfNecessary](#IfNecessary) | Gerekirse ZIP64 format uzantılarını kullanın. |
| [Always](#Always) | Her zaman ZIP64 format uzantılarını kullanın. |
### Asla {#Never}
```
public static final int Never
```

ZIP64 format uzantılarını kullanmayın.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```

Gerekirse ZIP64 format uzantılarını kullanın.

### Always {#Always}
```
public static final int Always
```

Her zaman ZIP64 format uzantılarını kullanın.