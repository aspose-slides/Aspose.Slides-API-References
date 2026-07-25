---
title: StaticCastArray()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された配列の要素を別の型にキャストします。From が SmartPtr オブジェクトである場合のオーバーライドです。
type: docs
weight: 2978
url: /ja/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) 関数


指定された配列の要素を別の型にキャストします。From が [SmartPtr](../smartptr/) オブジェクトである場合のオーバーライドです。

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| To | 指定された配列の要素をキャストする型 |
| From | キャスト対象となる配列要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | キャスト対象の要素を含む配列への共有ポインタ |

### 戻り値

**To** 型の要素を含む新しい配列へのポインタ（**from** の要素に相当）

非推奨
:   後方互換性のために追加されました。代わりに ExplicitCast を使用してください。

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) 関数


指定された配列の要素を別の型にキャストします。From が Boxable で To が [Object](../object/)[] の場合のオーバーライドです。

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| To | 指定された配列の要素をキャストする型 |
| From | キャスト対象となる配列要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | キャスト対象の要素を含む配列への共有ポインタ |

### 戻り値

**To** 型の要素を含む新しい配列へのポインタ（**from** の要素に相当）

非推奨
:   後方互換性のために追加されました。代わりに ExplicitCast を使用してください。

## 参照

* 型定義 [SharedPtr](../sharedptr/)
* クラス [Array](../array/)
* クラス [Object](../object/)
* 構造体 [IsSmartPtr](../issmartptr/)
* 構造体 [IsBoxable](../isboxable/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)