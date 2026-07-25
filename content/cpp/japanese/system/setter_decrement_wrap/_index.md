---
title: setter_decrement_wrap()
second_title: Aspose.Slides for C++ API リファレンス
description: この関数は、setter と getter が定義されたクラスのプロパティを対象とした C# の前置デクリメント式を、関数呼び出しに変換します。
type: docs
weight: 2861
url: /ja/system/setter_decrement_wrap/
---
## System::setter_decrement_wrap(T(*)(), void(*)(T)) 関数

この関数は、setter と getter が定義されたクラスのプロパティを対象とした C# の前置デクリメント式を、関数呼び出しに変換します。

```cpp
template<typename T> T System::setter_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | プロパティの型 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| pGetter | T(*)() | プロパティの getter フリー関数を指す関数ポインタ |
| pSetter | void(*)(T) | プロパティの setter フリー関数を指す関数ポインタ |

### 戻り値

インクリメント前のプロパティの値

## System::setter_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) 関数

この関数は、setter と getter が定義されたインスタンスのプロパティを対象とした C# の前置デクリメント式を、関数呼び出しに変換します（非 const getter 用のオーバーロード）。

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | プロパティの型 |
| Host | - 修正対象インスタンスのクラス |
| HostGet | - プロパティの getter が定義されている Host 自身、またはその基底型 |
| HostSet | - プロパティの setter が定義されている Host 自身、またはその基底型 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | getter と setter を呼び出す対象インスタンス |
| pGetter | T(HostGet::*)() | プロパティの getter 関数を指す関数ポインタ |
| pSetter | void(HostSet::*)(T) | プロパティの setter 関数を指す関数ポインタ |

### 戻り値

インクリメント前のプロパティの値

## System::setter_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) 関数

この関数は、setter と getter が定義されたインスタンスのプロパティを対象とした C# の前置デクリメント式を、関数呼び出しに変換します（const getter 用のオーバーロード）。

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | プロパティの型 |
| Host | - 修正対象インスタンスのクラス |
| HostConstGet | - プロパティの getter が定義されている Host 自身、またはその基底型 |
| HostSet | - プロパティの setter が定義されている Host 自身、またはその基底型 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | getter と setter を呼び出す対象インスタンス |
| pGetter | T(HostConstGet::*)() const | プロパティの getter 関数を指す関数ポインタ |
| pSetter | void(HostSet::*)(T) | プロパティの setter 関数を指す関数ポインタ |

### 戻り値

インクリメント前のプロパティの値

## 参照

* Namespace [System](../)
* Library [Aspose.Slides](../../)