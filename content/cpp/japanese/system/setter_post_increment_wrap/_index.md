---
title: setter_post_increment_wrap()
second_title: Aspose.Slides for C++ API リファレンス
description: Translator は、setter と getter が定義されたクラスのプロパティを対象とした C# の後置インクリメント式を、この関数の呼び出しに変換します。
type: docs
weight: 2848
url: /ja/system/setter_post_increment_wrap/
---
## System::setter_post_increment_wrap(T(*)(), void(*)(T)) 関数

Translator は、setter と getter が定義されたクラスのプロパティを対象とした C# の後置インクリメント式を、この関数の呼び出しに変換します。

```cpp
template<typename T> T System::setter_post_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
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

インクリメント前のプロパティの値

## System::setter_post_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) 関数

Translator は、setter と getter が定義されたインスタンスのプロパティを対象とした C# の後置インクリメント式を、この関数の呼び出しに変換します（非 const getter 用のオーバーロード）。

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | プロパティの型 |
| Host | - 変更対象インスタンスのクラス |
| HostGet | - プロパティの getter が定義されている Host 自身またはその基底型 |
| HostSet | - プロパティの setter が定義されている Host 自身またはその基底型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| host | Host *const | getter と setter を呼び出すインスタンス |
| pGetter | T(HostGet::*)() | プロパティの getter 関数を指す関数ポインタ |
| pSetter | void(HostSet::*)(T) | プロパティの setter 関数を指す関数ポインタ |

### 戻り値

インクリメント前のプロパティの値

## System::setter_post_increment_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) 関数

Translator は、setter と getter が定義されたインスタンスのプロパティを対象とした C# の後置インクリメント式を、この関数の呼び出しに変換します（const getter 用のオーバーロード）。

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | プロパティの型 |
| Host | - 変更対象インスタンスのクラス |
| HostConstGet | - プロパティの getter が定義されている Host 自身またはその基底型 |
| HostSet | - プロパティの setter が定義されている Host 自身またはその基底型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| host | Host *const | getter と setter を呼び出すインスタンス |
| pGetter | T(HostConstGet::*)() const | プロパティの getter 関数を指す関数ポインタ |
| pSetter | void(HostSet::*)(T) | プロパティの setter 関数を指す関数ポインタ |

### 戻り値

インクリメント前のプロパティの値

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)