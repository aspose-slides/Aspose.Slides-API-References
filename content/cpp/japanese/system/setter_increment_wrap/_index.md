---
title: setter_increment_wrap()
second_title: Aspose.Slides for C++ API リファレンス
description: この関数は、setter と getter が定義されたクラスのプロパティを対象とした C# のインクリメント式を変換し、呼び出します。
type: docs
weight: 2835
url: /ja/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) 関数

この関数は、setter と getter が定義されたクラスのプロパティを対象とした C# のインクリメント式を変換し、呼び出します。

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | プロパティの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pGetter | T(*)() | プロパティの getter フリー関数を指す関数ポインタ |
| pSetter | void(*)(T) | プロパティの setter フリー関数を指す関数ポインタ |

### 戻り値

プロパティのインクリメント後の値

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) 関数

この関数は、setter と getter が定義されたクラスのプロパティを対象とした C# のインクリメント式を変換し、呼び出します。

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | プロパティの型 |
| Host | - 修正対象インスタンスのクラス |
| HostGet | - Host 自身、またはプロパティの getter が定義されているその基底型 |
| HostSet | - Host 自身、またはプロパティの setter が定義されているその基底型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| host | Host *const | プロパティをインクリメントするオブジェクトへのポインタ |
| pGetter | T(HostGet::*)() | プロパティの getter メソッドを指す関数ポインタ |
| pSetter | void(HostSet::*)(T) | プロパティの setter メソッドを指す関数ポインタ |

### 戻り値

プロパティのインクリメント後の値

## 関連項目

* Namespace [System](../)
* Library [Aspose.Slides](../../)