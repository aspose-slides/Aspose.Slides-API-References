---
title: TypeInfo()
second_title: Aspose.Slides for C++ API リファレンス
description: デフォルトコンストラクタ（型は設定されていません）。
type: docs
weight: 40
url: /ja/system/typeinfo/typeinfo/
---
## TypeInfo::TypeInfo() コンストラクタ

デフォルトコンストラクタ（型は設定されていません）。

```cpp
System::TypeInfo::TypeInfo()
```

## TypeInfo::TypeInfo(std::nullptr_t) コンストラクタ

ヌルオブジェクトコンストラクタ（型は設定されていません）。

```cpp
System::TypeInfo::TypeInfo(std::nullptr_t)
```

## TypeInfo::TypeInfo(const char_t *) コンストラクタ

コンストラクタ。

```cpp
System::TypeInfo::TypeInfo(const char_t *name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | const char_t * | 型名。 |

## TypeInfo::TypeInfo(const char_t *, uint32_t) コンストラクタ

コンストラクタ。

```cpp
System::TypeInfo::TypeInfo(const char_t *name, uint32_t hash)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | const char_t * | 型名。 |
| hash | **uint32_t** | 型名ハッシュ。 |

## TypeInfo::TypeInfo(const std::type_info\&) コンストラクタ

コンストラクタ。

```cpp
System::TypeInfo::TypeInfo(const std::type_info &info)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| info | const std::type_info\& | 型に関する情報。 |

## 参照

* クラス [TypeInfo](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)