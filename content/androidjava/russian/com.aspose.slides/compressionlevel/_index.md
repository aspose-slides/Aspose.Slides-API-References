---
title: CompressionLevel
second_title: Справочник API Aspose.Slides для Android через Java
description: Указывает уровни сжатия ZIP для файла OpenXML.
type: docs
url: /ru/com.aspose.slides/compressionlevel/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CompressionLevel extends System.Enum
```

Определяет уровни сжатия ZIP для файла OpenXML. Более высокие уровни обеспечивают лучшее сжатие за счёт более медленной обработки.
## Поля

| Поле | Описание |
| --- | --- |
| [None](#None) | No compression is applied. |
| [Level1](#Level1) | Fastest compression with the lowest compression ratio. |
| [Level2](#Level2) | Faster compression with slightly better compression ratio than [Level1](../../com.aspose.slides/compressionlevel\#Level1). |
| [Level3](#Level3) | Provides better compression than [Level2](../../com.aspose.slides/compressionlevel\#Level2) with moderate performance impact. |
| [Level4](#Level4) | Provides better compression than [Level3](../../com.aspose.slides/compressionlevel\#Level3). |
| [Level5](#Level5) | Provides improved compression over [Level4](../../com.aspose.slides/compressionlevel\#Level4) with additional processing time. |
| [Level6](#Level6) | Standard compression, offering a good balance between compression speed and file size. |
| [Level7](#Level7) | Provides higher compression than [Level6](../../com.aspose.slides/compressionlevel\#Level6) with slower processing. |
| [Level8](#Level8) | Provides higher compression than [Level7](../../com.aspose.slides/compressionlevel\#Level7). |
| [Level9](#Level9) | Maximum compression. |
### None {#None}
```
public static final int None
```

Сжатие не применяется. Файлы хранятся без изменений.

### Level1 {#Level1}
```
public static final int Level1
```

Самое быстрое сжатие с наименьшим коэффициентом сжатия.

### Level2 {#Level2}
```
public static final int Level2
```

Более быстрое сжатие с немного лучшим коэффициентом сжатия, чем [Level1](../../com.aspose.slides/compressionlevel\#Level1).

### Level3 {#Level3}
```
public static final int Level3
```

Обеспечивает лучшее сжатие, чем [Level2](../../com.aspose.slides/compressionlevel\#Level2), с умеренным влиянием на производительность.

### Level4 {#Level4}
```
public static final int Level4
```

Обеспечивает лучшее сжатие, чем [Level3](../../com.aspose.slides/compressionlevel\#Level3).

### Level5 {#Level5}
```
public static final int Level5
```

Обеспечивает улучшенное сжатие по сравнению с [Level4](../../com.aspose.slides/compressionlevel\#Level4) с дополнительным временем обработки.

### Level6 {#Level6}
```
public static final int Level6
```

Стандартное сжатие, предоставляющее хороший баланс между скоростью сжатия и размером файла. Уровень сжатия по умолчанию.

### Level7 {#Level7}
```
public static final int Level7
```

Обеспечивает более высокое сжатие, чем [Level6](../../com.aspose.slides/compressionlevel\#Level6), с более медленной обработкой.

### Level8 {#Level8}
```
public static final int Level8
```

Обеспечивает более высокое сжатие, чем [Level7](../../com.aspose.slides/compressionlevel\#Level7).

### Level9 {#Level9}
```
public static final int Level9
```

Максимальное сжатие. Создаёт самый маленький размер файла при самой медленной скорости обработки.