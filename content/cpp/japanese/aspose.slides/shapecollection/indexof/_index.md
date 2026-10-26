---
title: IndexOf()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクション内で指定された shape が最初に出現する位置のゼロベースインデックスを返します。
type: docs
weight: 313
url: /ja/aspose.slides/shapecollection/indexof/
---
## ShapeCollection::IndexOf(System::SharedPtr\<IShape\>) メソッド


コレクション内で指定された shape が最初に出現する位置のゼロベースインデックスを返します。

```cpp
int32_t Aspose::Slides::ShapeCollection::IndexOf(System::SharedPtr<IShape> shape) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | コレクション内で検索する shape。 |

### 戻り値

見つかった場合は shape コレクション内で最初に出現する shape のゼロベースインデックスを返します。見つからない場合は \\u20131 を返します。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IShape](../../ishape/)
* クラス [ShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)