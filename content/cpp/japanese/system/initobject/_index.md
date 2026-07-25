---
title: InitObject()
second_title: Aspose.Slides for C++ API リファレンス
description: 共有所有権でオブジェクトの初期化を開始します。
type: docs
weight: 2263
url: /ja/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) 関数


オブジェクトの共有所有権での初期化を開始します。

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 初期化するオブジェクトの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) を初期化する |

## 戻り値

共有ポインタ構築用に設定された ObjectBuilder

## 備考



[Object](../object/) の初期化は [Get()](../get/) 呼び出しで完了しなければなりません

## 関連項目

* typedef [SharedPtr](../sharedptr/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)