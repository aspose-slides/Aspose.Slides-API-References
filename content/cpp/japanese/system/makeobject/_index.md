---
title: MakeObject()
second_title: Aspose.Slides for C++ API リファレンス
description: ヒープ上にオブジェクトを作成し、shared ポインタを返します。
type: docs
weight: 2887
url: /ja/system/makeobject/
---
## System::MakeObject(Args\&&...) 関数


ヒープ上にオブジェクトを作成し、shared ポインタを返します。

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | インスタンス化するクラス。 |
| Args | コンストラクタ引数の型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| args | Args\&&... | コンストラクタ引数。 |

### 戻り値

[SmartPtr](../smartptr/) 新しく作成されたオブジェクトへの参照、常に共有モードで。

## System::MakeObject(Args\&&...) 関数


ヒープ上にオブジェクトを作成し、shared ポインタを返します。

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | [SmartPtr](../smartptr/) インスタンス化するクラス。 |
| Args | コンストラクタ引数の型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| args | Args\&&... | コンストラクタ引数。 |

### 戻り値

[SmartPtr](../smartptr/) 新しく作成されたオブジェクトへの参照、常に共有モードで。

## 参照

* クラス [SmartPtr](../smartptr/)
* 構造体 [IsSmartPtr](../issmartptr/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)