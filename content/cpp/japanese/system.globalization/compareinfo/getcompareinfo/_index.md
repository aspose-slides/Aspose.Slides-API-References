---
title: GetCompareInfo()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたカルチャに関連付けられ、指定されたアセンブリの文字列比較メソッドを使用する CompareInfo を取得します。
type: docs
weight: 183
url: /ja/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) メソッド

指定されたカルチャに関連付けられ、指定されたアセンブリの文字列比較メソッドを使用する [CompareInfo](../) を取得します。

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| culture | int | カルチャ識別子 (LCID)。 |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | 文字列比較メソッドを含むアセンブリ。 |

### 戻り値

[CompareInfo](../) オブジェクト。

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) メソッド

指定されたカルチャに関連付けられ、指定されたアセンブリの文字列比較メソッドを使用する [CompareInfo](../) を取得します。

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | カルチャ名。 |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | 文字列比較メソッドを含むアセンブリ。 |

### 戻り値

[CompareInfo](../) オブジェクト。

## CompareInfo::GetCompareInfo(int) メソッド

指定されたカルチャに関連付けられた [CompareInfo](../) を取得します。

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| culture | int | カルチャ識別子 (LCID)。 |

### 戻り値

[CompareInfo](../) オブジェクト。

## CompareInfo::GetCompareInfo(const String\&) メソッド

指定されたカルチャに関連付けられた [CompareInfo](../) を取得します。

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | カルチャ名。 |

### 戻り値

[CompareInfo](../) オブジェクト。

## 参照

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Assembly](../../../system.reflection/assembly/)
* クラス [CompareInfo](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)