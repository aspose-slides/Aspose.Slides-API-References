---
title: Guid()
second_title: Aspose.Slides for C++ API リファレンス
description: すべてゼロで構成された GUID を表すオブジェクトを構築します。
type: docs
weight: 1
url: /ja/system/guid/guid/
---
## Guid::Guid() コンストラクタ

すべてゼロの GUID を表すオブジェクトを構築します。

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) コンストラクタ

符号なし 8 ビット整数値の配列として指定された GUID を表すオブジェクトを構築します。

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | GUID の個々のバイトを含むバイト配列 |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) コンストラクタ

符号なし 8 ビット整数値の配列ビューとして指定された GUID を表すオブジェクトを構築します。

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | GUID の個々のバイトを含むバイト配列 |

## Guid::Guid(const String\&) コンストラクタ

文字列として指定された GUID を表すオブジェクトを構築します。

```cpp
System::Guid::Guid(const String &g)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| g | const [String](../../string/)\& | 構築されるオブジェクトが表す GUID の文字列表現 |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) コンストラクタ

指定された GUID コンポーネントから [Guid](../) クラスのインスタンスを構築します。

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| a | **int32_t** | GUID のビット 0-31 |
| b | **int16_t** | GUID のビット 32-47 |
| c | **int16_t** | GUID のビット 48-63 |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | GUID のビット 64-127 を含むバイト配列 |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) コンストラクタ

指定された GUID コンポーネントから [Guid](../) クラスのインスタンスを構築します。

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| a | **int32_t** | GUID のビット 0-31 |
| b | **int16_t** | GUID のビット 32-47 |
| c | **int16_t** | GUID のビット 48-63 |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | GUID のビット 64-127 を含むバイト配列ビュー |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) コンストラクタ

指定された符号なし整数およびバイトから [Guid](../) クラスのインスタンスを構築します。

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| a | **int32_t** | GUID のビット 0-31 |
| b | **int16_t** | GUID のビット 32-47 |
| c | **int16_t** | GUID のビット 48-63 |
| d | **uint8_t** | GUID のビット 64-71 |
| e | **uint8_t** | GUID のビット 72-79 |
| f | **uint8_t** | GUID のビット 80-87 |
| g | **uint8_t** | GUID のビット 88-95 |
| h | **uint8_t** | GUID のビット 96-103 |
| i | **uint8_t** | GUID のビット 104-111 |
| j | **uint8_t** | GUID のビット 112-119 |
| k | **uint8_t** | GUID のビット 120-127 |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) コンストラクタ

指定された符号なし整数およびバイトから [Guid](../) クラスのインスタンスを構築します。

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| a | **uint32_t** | GUID のビット 0-31 |
| b | **uint16_t** | GUID のビット 32-47 |
| c | **uint16_t** | GUID のビット 48-63 |
| d | **uint8_t** | GUID のビット 64-71 |
| e | **uint8_t** | GUID のビット 72-79 |
| f | **uint8_t** | GUID のビット 80-87 |
| g | **uint8_t** | GUID のビット 88-95 |
| h | **uint8_t** | GUID のビット 96-103 |
| i | **uint8_t** | GUID のビット 104-111 |
| j | **uint8_t** | GUID のビット 112-119 |
| k | **uint8_t** | GUID のビット 120-127 |

## Guid::Guid(const Guid\&) コンストラクタ

指定されたオブジェクトと同じ GUID を表すオブジェクトを構築します。

```cpp
System::Guid::Guid(const Guid &guid)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| guid | const [Guid](../)\& | GUID の値をコピーする [Guid](../) オブジェクト |

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Guid](../)
* Class [String](../../string/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)