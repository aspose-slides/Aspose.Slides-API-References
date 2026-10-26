---
title: setter_wrap()
second_title: Aspose.Slides for C++ API リファレンス
description: 型変換を伴う静的セッター関数のオーバーロード。
type: docs
weight: 2822
url: /ja/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) 関数

型変換を伴う静的セッター関数のオーバーロード。

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 値の型。 |
| T2 | セッター関数が期待する型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pSetter | void(*)(T2) | 静的セッター関数参照。 |
| value | T | 設定する値。 |

### 戻り値

値を設定します。

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) 関数

型変換を伴うインスタンス セッター関数のオーバーロード。

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 値の型。 |
| T2 | セッター関数が期待する型。 |
| Host | インスタンスの型。 |
| HostSet | - Host 自体、またはプロパティのセッターが定義されているベース型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| host | Host *const | [Object](../object/) のセッター関数を呼び出す対象。 |
| pSetter | void(HostSet::*)(T2) | セッター関数参照。 |
| value | T | 設定する値。 |

### 戻り値

値を設定します。

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)