---
title: Write()
second_title: مرجع API Aspose.Slides للغة C++
description: يكتب القيمة الصحيحة غير الموقعة 8-بت المحددة إلى تدفق الإخراج.
type: docs
weight: 92
url: /ar/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) طريقة

يكتب القيمة الصحيحة غير الموقعة 8-بت المحددة إلى تدفق الإخراج.

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | **uint8_t** | القيمة التي سيتم كتابتها |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) طريقة

يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايتات المحددة إلى تدفق الإخراج.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | المصفوفة التي تحتوي على البايتات التي سيتم كتابتها |
| index | int | مؤشر 0-مبني يُشير إلى العنصر في **buffer** حيث يبدأ النطاق الفرعي للكتابة |
| count | int | عدد العناصر في النطاق الفرعي للكتابة؛ -1 يعني أن النطاق الفرعي ينتهي عند نهاية مصفوفة **buffer** |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) طريقة

يكتب النطاق الفرعي المحدد من أحرف UTF-16 من مصفوفة الأحرف المحددة إلى تدفق الإخراج.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | المصفوفة التي تحتوي على الأحرف التي سيتم كتابتها |
| index | int | مؤشر 0-مبني يُشير إلى العنصر في **buffer** حيث يبدأ النطاق الفرعي للكتابة |
| count | int | عدد الأحرف في النطاق الفرعي للكتابة؛ -1 يعني أن النطاق الفرعي ينتهي عند نهاية مصفوفة **buffer** |

## BinaryWriter::Write(bool) طريقة

يكتب بايتًا واحدًا بقيمة 0 إذا كانت **value** 'true' و1 إذا كانت **value** 'false' إلى تدفق الإخراج.

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | **bool** | القيمة المنطقية التي تحدد قيمة البايت التي سيتم كتابتها إلى تدفق الإخراج |

## BinaryWriter::Write(char16_t) طريقة

يكتب القيمة المحددة للرمز عريض 16-بت إلى تدفق الإخراج.

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | char16_t | القيمة التي سيتم كتابتها |

## BinaryWriter::Write(int16_t) طريقة

يكتب القيمة المحددة للعدد الصحيح 16-بت إلى تدفق الإخراج.

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | **int16_t** | القيمة التي سيتم كتابتها |

## BinaryWriter::Write(int) طريقة

يكتب القيمة المحددة للعدد الصحيح 32-بت إلى تدفق الإخراج.

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int | القيمة التي سيتم كتابتها |

## BinaryWriter::Write(int64_t) طريقة

يكتب القيمة المحددة للعدد الصحيح 64-بت إلى تدفق الإخراج.

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | **int64_t** | القيمة التي سيتم كتابتها |

## BinaryWriter::Write(uint16_t) طريقة

يكتب القيمة المحددة للعدد الصحيح غير الموقّع 16-بت إلى تدفق الإخراج.

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | **uint16_t** | القيمة التي سيتم كتابتها |

## BinaryWriter::Write(uint32_t) طريقة

يكتب القيمة المحددة للعدد الصحيح غير الموقّع 32-بت إلى تدفق الإخراج.

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | **uint32_t** | القيمة التي سيتم كتابتها |

## BinaryWriter::Write(uint64_t) طريقة

يكتب القيمة المحددة للعدد الصحيح غير الموقّع 64-بت إلى تدفق الإخراج.

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | **uint64_t** | القيمة التي سيتم كتابتها |

## BinaryWriter::Write(float) طريقة

يكتب القيمة المحددة للعدد العشري ذو الدقة المفردة إلى تدفق الإخراج.

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | **float** | القيمة التي سيتم كتابتها |

## BinaryWriter::Write(double) طريقة

يكتب القيمة المحددة للعدد العشري ذو الدقة المزدوجة إلى تدفق الإخراج.

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | **double** | القيمة التي سيتم كتابتها |

## BinaryWriter::Write(const Decimal\&) طريقة

يكتب تمثيل البايت للقيمة المحددة [Decimal](../../../system/decimal/) إلى تدفق الإخراج.

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | القيمة التي سيتم كتابتها |

## BinaryWriter::Write(const String\&) طريقة

يكتب سلسلة بطول مُسبق مُشفرة بالتشفير الحالي إلى تدفق الإخراج.

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | السلسلة التي سيتم كتابتها |

## BinaryWriter::Write(const char_t *) طريقة

يكتب سلسلة بطول مُسبق مُشفرة بالتشفير الحالي إلى تدفق الإخراج.

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | const char_t * | سلسلة C التي سيتم كتابتها |

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* الفئة [BinaryWriter](../)
* الفئة [Decimal](../../../system/decimal/)
* الفئة [String](../../../system/string/)
* المجال [System::IO](../../)
* المكتبة [Aspose.Slides](../../../)