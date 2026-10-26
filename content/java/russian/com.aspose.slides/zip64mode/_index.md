---
title: Zip64Mode
second_title: Aspose.Slides для Java справочник API
description: Указывает, когда использовать расширения формата ZIP64 для файла OpenXML.
type: docs
url: /ru/com.aspose.slides/zip64mode/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

Указывает, когда использовать расширения формата ZIP64 для файла OpenXML.

--------------------

Файл OpenXML представляет собой ZIP-архив, у которого есть ограничение в 4 ГБ (2^32 байта) на несжатый размер файла, сжатый размер файла и общий размер архива, а также ограничение в 65 535 (2^16-1) файлов в архиве. Расширения формата ZIP64 увеличивают эти ограничения до 2^64.
## Поля

| Поле | Описание |
| --- | --- |
| [Never](#Never) | Не использовать расширения формата ZIP64. |
| [IfNecessary](#IfNecessary) | Использовать расширения формата ZIP64 при необходимости. |
| [Always](#Always) | Всегда использовать расширения формата ZIP64. |
### Never {#Never}
```
public static final int Never
```

Не использовать расширения формата ZIP64.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```

Использовать расширения формата ZIP64 при необходимости.

### Always {#Always}
```
public static final int Always
```

Всегда использовать расширения формата ZIP64.