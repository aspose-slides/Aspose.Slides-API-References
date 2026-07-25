---
title: CompareTo()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のインスタンスを同じ型の別のオブジェクトと比較します。
type: docs
weight: 66
url: /ja/aspose.slides/tab/compareto/
---
## Tab::CompareTo(System::SharedPtr\<ITab\>) メソッド


現在のインスタンスを同じ型の別のオブジェクトと比較します。

```cpp
int32_t Aspose::Slides::Tab::CompareTo(System::SharedPtr<ITab> obj) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | このインスタンスと比較するオブジェクトです。 |

### 戻り値

比較対象の相対順序を示す32ビット整数です。戻り値は以下の意味を持ちます：
* < 0 - このインスタンスは obj 未満です。
* = 0 - このインスタンスは obj と等しいです。
* > 0 - このインスタンスは obj より大きいです。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ITab](../../itab/)
* クラス [Tab](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)