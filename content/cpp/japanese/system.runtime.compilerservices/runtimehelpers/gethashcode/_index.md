---
title: GetHashCode()
second_title: Aspose.Slides for C++ API リファレンス
description: "任意の型のハッシュコードを取得します。これを行うために Object::GetHashCode() を呼び出します。"
type: docs
weight: 1
url: /ja/system.runtime.compilerservices/runtimehelpers/gethashcode/
---
## RuntimeHelpers::GetHashCode(SmartPtr\<T\> const\&) メソッド

Gets hash code on arbitrary type. Calls [Object::GetHashCode()](../../../system/object/gethashcode/) to do so.

```cpp
template<typename T> static int System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode(SmartPtr<T> const &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | ハッシュコードを取得する型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | [SmartPtr](../../../system/smartptr/)\<T\> const\& | [Object](../../../system/object/) から情報を取得します。 |

### 戻り値

対象実装によって計算されたハッシュコードの値。

## 参照

* クラス [SmartPtr](../../../system/smartptr/)
* クラス [RuntimeHelpers](../)
* 名前空間 [System::Runtime::CompilerServices](../../)
* ライブラリ [Aspose.Slides](../../../)