---
title: Zip64Mode
second_title: Справочник API Aspose.Slides для Android через Java
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

Файл OpenXML — это ZIP-архив, который имеет ограничение в 4 ГБ (2^32 байта) на несжатый размер файла, сжатый размер файла и общий размер архива, а также ограничение в 65 535 (2^16-1) файлов в архиве. Расширения формата ZIP64 увеличивают ограничения до 2^64.
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