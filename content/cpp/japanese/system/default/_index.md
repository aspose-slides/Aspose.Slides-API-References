---
title: Default()
second_title: Aspose.Slides for C++ API リファレンス
description: 例外型の単一のデフォルト構築インスタンスへの参照を返します。
type: docs
weight: 2224
url: /ja/system/default/
---
## System::Default() 関数

例外型の単一のデフォルト構築インスタンスへの参照を返します。

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Template parameters

| パラメータ | 説明 |
| --- | --- |
| T | インスタンスが返される型 |

## System::Default() 関数

例外でない型の単一のデフォルト構築インスタンスへの参照を返します。

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Template parameters

| パラメータ | 説明 |
| --- | --- |
| T | インスタンスが返される型 |

## 参照

* 構造体 [IsExceptionWrapper](../isexceptionwrapper/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)