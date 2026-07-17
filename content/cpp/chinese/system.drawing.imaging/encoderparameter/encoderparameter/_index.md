---
title: EncoderParameter()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个 EncoderParameter 类的新实例。
type: docs
weight: 1
url: /zh/system.drawing.imaging/encoderparameter/encoderparameter/
---
## EncoderParameter::EncoderParameter() 构造函数

构造一个 [EncoderParameter](../) 类的新实例。

```cpp
System::Drawing::Imaging::EncoderParameter::EncoderParameter()
```

## EncoderParameter::EncoderParameter(const SharedPtr\<Encoder\>\&, uint8_t, bool) 构造函数

构造一个 [EncoderParameter](../) 类的新实例。

```cpp
System::Drawing::Imaging::EncoderParameter::EncoderParameter(const SharedPtr<Encoder> &encoder, uint8_t value, bool undefined=false)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encoder | const [SharedPtr](../../../system/sharedptr/)\<[Encoder](../../encoder/)\>\& | 指定参数类别 |
| value | **uint8_t** | 一个未签名的 8 位整数值，由创建的对象表示 |
| undefined | **bool** | 如果 **value** 应被视为未定义类型则为真，否则为假 |

## EncoderParameter::EncoderParameter(const SharedPtr\<Encoder\>\&, int16_t) 构造函数

构造一个 [EncoderParameter](../) 类的新实例。

```cpp
System::Drawing::Imaging::EncoderParameter::EncoderParameter(const SharedPtr<Encoder> &encoder, int16_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encoder | const [SharedPtr](../../../system/sharedptr/)\<[Encoder](../../encoder/)\>\& | 指定参数类别 |
| value | **int16_t** | 一个 16 位整数值，由创建的对象表示 |

## EncoderParameter::EncoderParameter(const SharedPtr\<Encoder\>\&, int64_t) 构造函数

构造一个 [EncoderParameter](../) 类的新实例。

```cpp
System::Drawing::Imaging::EncoderParameter::EncoderParameter(const SharedPtr<Encoder> &encoder, int64_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encoder | const [SharedPtr](../../../system/sharedptr/)\<[Encoder](../../encoder/)\>\& | 指定参数类别 |
| value | **int64_t** | 一个 64 位整数值，由创建的对象表示 |

## EncoderParameter::EncoderParameter(const SharedPtr\<Encoder\>\&, int32_t) 构造函数

构造一个 [EncoderParameter](../) 类的新实例。

```cpp
System::Drawing::Imaging::EncoderParameter::EncoderParameter(const SharedPtr<Encoder> &encoder, int32_t value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encoder | const [SharedPtr](../../../system/sharedptr/)\<[Encoder](../../encoder/)\>\& | 指定参数类别 |
| value | **int32_t** | 一个 32 位整数值，由创建的对象表示 |

## EncoderParameter::EncoderParameter(const SharedPtr\<Encoder\>\&, int32_t, int32_t) 构造函数

构造一个表示分数的 [EncoderParameter](../) 类的新实例。

```cpp
System::Drawing::Imaging::EncoderParameter::EncoderParameter(const SharedPtr<Encoder> &encoder, int32_t numerator, int32_t denominator)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encoder | const [SharedPtr](../../../system/sharedptr/)\<[Encoder](../../encoder/)\>\& | 指定参数类别 |
| numerator | **int32_t** | 表示对象的分子 |
| denominator | **int32_t** | 表示对象的分母 |

## EncoderParameter::EncoderParameter(const SharedPtr\<Encoder\>\&, int64_t, int64_t) 构造函数

构造一个表示整数范围的 [EncoderParameter](../) 类的新实例。

```cpp
System::Drawing::Imaging::EncoderParameter::EncoderParameter(const SharedPtr<Encoder> &encoder, int64_t rangebegin, int64_t rangeend)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encoder | const [SharedPtr](../../../system/sharedptr/)\<[Encoder](../../encoder/)\>\& | 指定参数类别 |
| rangebegin | **int64_t** | 范围中的最小值 |
| rangeend | **int64_t** | 范围中的最大值 |

## EncoderParameter::EncoderParameter(const SharedPtr\<Encoder\>\&, int32_t, int32_t, int32_t, int32_t) 构造函数

构造一个表示分数范围的 [EncoderParameter](../) 类的新实例。

```cpp
System::Drawing::Imaging::EncoderParameter::EncoderParameter(const SharedPtr<Encoder> &encoder, int32_t numerator1, int32_t demoninator1, int32_t numerator2, int32_t demoninator2)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encoder | const [SharedPtr](../../../system/sharedptr/)\<[Encoder](../../encoder/)\>\& | 指定参数类别 |
| numerator1 | **int32_t** | 范围中最小分数的分子 |
| numerator2 | **int32_t** | 范围中最大分数的分子 |
| demoninator1 | **int32_t** | 范围中最小分数的分母 |
| demoninator2 | **int32_t** | 范围中最大分数的分母 |

## EncoderParameter::EncoderParameter(const SharedPtr\<Encoder\>\&, const String\&) 构造函数

构造一个 [EncoderParameter](../) 类的新实例。

```cpp
System::Drawing::Imaging::EncoderParameter::EncoderParameter(const SharedPtr<Encoder> &encoder, const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encoder | const [SharedPtr](../../../system/sharedptr/)\<[Encoder](../../encoder/)\>\& | 指定参数类别 |
| value | const [String](../../../system/string/)\& | 由创建的对象表示的字符串 |

## EncoderParameter::EncoderParameter(const SharedPtr\<Encoder\>\&, const ArrayPtr\<uint8_t\>\&, bool) 构造函数

构造一个表示值数组的 [EncoderParameter](../) 类的新实例。

```cpp
System::Drawing::Imaging::EncoderParameter::EncoderParameter(const SharedPtr<Encoder> &encoder, const ArrayPtr<uint8_t> &value, bool undefined=false)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encoder | const [SharedPtr](../../../system/sharedptr/)\<[Encoder](../../encoder/)\>\& | 指定参数类别 |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 一个未签名的 8 位整数数组，由创建的对象表示 |
| undefined | **bool** | 如果 **value** 数组中的值应被视为未定义类型则为真，否则为假 |

## EncoderParameter::EncoderParameter(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int16_t\>\&) 构造函数

构造一个表示值数组的 [EncoderParameter](../) 类的新实例。

```cpp
System::Drawing::Imaging::EncoderParameter::EncoderParameter(const SharedPtr<Encoder> &encoder, const ArrayPtr<int16_t> &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encoder | const [SharedPtr](../../../system/sharedptr/)\<[Encoder](../../encoder/)\>\& | 指定参数类别 |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**int16_t**\>\& | 一个 16 位整数数组，由创建的对象表示 |

## EncoderParameter::EncoderParameter(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int64_t\>\&) 构造函数

构造一个表示值数组的 [EncoderParameter](../) 类的新实例。

```cpp
System::Drawing::Imaging::EncoderParameter::EncoderParameter(const SharedPtr<Encoder> &encoder, const ArrayPtr<int64_t> &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encoder | const [SharedPtr](../../../system/sharedptr/)\<[Encoder](../../encoder/)\>\& | 指定参数类别 |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**int64_t**\>\& | 一个 64 位整数数组，由创建的对象表示 |

## EncoderParameter::EncoderParameter(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&) 构造函数

构造一个表示分数数组的 [EncoderParameter](../) 类的新实例。

```cpp
System::Drawing::Imaging::EncoderParameter::EncoderParameter(const SharedPtr<Encoder> &encoder, const ArrayPtr<int32_t> &numerator, const ArrayPtr<int32_t> &denominator)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encoder | const [SharedPtr](../../../system/sharedptr/)\<[Encoder](../../encoder/)\>\& | 指定参数类别 |
| numerator | const [ArrayPtr](../../../system/arrayptr/)\<**int32_t**\>\& | 一个分子数组，由创建的对象表示的分数 |
| denominator | const [ArrayPtr](../../../system/arrayptr/)\<**int32_t**\>\& | 一个分母数组，由创建的对象表示的分数 |

## EncoderParameter::EncoderParameter(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int64_t\>\&, const ArrayPtr\<int64_t\>\&) 构造函数

构造一个表示整数范围数组的 [EncoderParameter](../) 类的新实例。

```cpp
System::Drawing::Imaging::EncoderParameter::EncoderParameter(const SharedPtr<Encoder> &encoder, const ArrayPtr<int64_t> &rangebegin, const ArrayPtr<int64_t> &rangeend)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encoder | const [SharedPtr](../../../system/sharedptr/)\<[Encoder](../../encoder/)\>\& | 指定参数类别 |
| rangebegin | const [ArrayPtr](../../../system/arrayptr/)\<**int64_t**\>\& | 一个数组，包含每个范围的最小值 |
| rangeend | const [ArrayPtr](../../../system/arrayptr/)\<**int64_t**\>\& | 一个数组，包含每个范围的最大值 |

## EncoderParameter::EncoderParameter(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&) 构造函数

构造一个表示分数范围数组的 [EncoderParameter](../) 类的新实例。

```cpp
System::Drawing::Imaging::EncoderParameter::EncoderParameter(const SharedPtr<Encoder> &encoder, const ArrayPtr<int32_t> &numerator1, const ArrayPtr<int32_t> &denominator1, const ArrayPtr<int32_t> &numerator2, const ArrayPtr<int32_t> &denominator2)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encoder | const [SharedPtr](../../../system/sharedptr/)\<[Encoder](../../encoder/)\>\& | 指定参数类别 |
| numerator1 | const [ArrayPtr](../../../system/arrayptr/)\<**int32_t**\>\& | 一个数组，包含每个范围中最小分数的分子 |
| numerator2 | const [ArrayPtr](../../../system/arrayptr/)\<**int32_t**\>\& | 一个数组，包含每个范围中分数的分子 |
| denominator1 | const [ArrayPtr](../../../system/arrayptr/)\<**int32_t**\>\& | 一个数组，包含每个范围中最小分数的分母 |
| denominator2 | const [ArrayPtr](../../../system/arrayptr/)\<**int32_t**\>\& | 一个数组，包含每个范围中最大分数的分母 |

## EncoderParameter::EncoderParameter(const SharedPtr\<Encoder\>\&, int, EncoderParameterValueType, void *) 构造函数

构造一个表示从指定缓冲区读取的指定类型的指定数量值的 [EncoderParameter](../) 类的新实例。

```cpp
System::Drawing::Imaging::EncoderParameter::EncoderParameter(const SharedPtr<Encoder> &encoder, int numberValues, EncoderParameterValueType type, void *value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encoder | const [SharedPtr](../../../system/sharedptr/)\<[Encoder](../../encoder/)\>\& | 指定参数类别 |
| numberValues | int | 指定值的数量 |
| type | [EncoderParameterValueType](../../encoderparametervaluetype/) | 指定值的类型 |
| value | void * | 指向读取值的缓冲区的指针 |

## 另见

* Enum [EncoderParameterValueType](../../encoderparametervaluetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [EncoderParameter](../)
* Class [Encoder](../../encoder/)
* Class [String](../../../system/string/)
* Namespace [System::Drawing::Imaging](../../)
* Library [Aspose.Slides](../../../)