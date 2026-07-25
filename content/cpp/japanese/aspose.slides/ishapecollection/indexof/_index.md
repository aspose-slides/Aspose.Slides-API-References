---
title: IndexOf()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクション内で指定されたシェイプが最初に出現する位置のゼロベースインデックスを返します。
type: docs
weight: 274
url: /ja/aspose.slides/ishapecollection/indexof/
---
## IShapeCollection::IndexOf(System::SharedPtr\<IShape\>) メソッド

コレクション内で指定されたシェイプが最初に出現する位置のゼロベースインデックスを返します。

```cpp
virtual int32_t Aspose::Slides::IShapeCollection::IndexOf(System::SharedPtr<IShape> shape)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | コレクション内で検索するシェイプ。 |

### 戻り値

シェイプコレクション内でシェイプが見つかった場合はその最初の出現位置のゼロベースインデックスを返し、見つからない場合は \\u20131 を返します。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IShape](../../ishape/)
* クラス [IShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)