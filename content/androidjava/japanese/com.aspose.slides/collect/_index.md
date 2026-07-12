---
title: Collect
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: さまざまなタイプのモデルオブジェクトを収集することを目的としたメソッドのグループを表します。
type: docs
url: /ja/com.aspose.slides/collect/
---
**継承:**
java.lang.Object
```
public class Collect
```

[Presentation](../../com.aspose.slides/presentation)から異なるタイプのモデルオブジェクトを収集することを目的としたメソッドのグループを表します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... シェイプの書式設定やその他のプロパティを変更します
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Collect()](#Collect--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | [Presentation](../../com.aspose.slides/presentation)内の[Shape](../../com.aspose.slides/shape)のすべてのインスタンスを収集します。 |
### Collect() {#Collect--}
```
public Collect()
```

### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```

[Presentation](../../com.aspose.slides/presentation)内の[Shape](../../com.aspose.slides/shape)のすべてのインスタンスを収集します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // shape が AutoShape の場合、黒の実線境界線を追加します
>          if (shape instanceof AutoShape)
>          {
>              AutoShape autoShape = (AutoShape)shape;
>              autoShape.getLineFormat().setStyle(LineStyle.Single);
>              autoShape.getLineFormat().setWidth(10f);
>              autoShape.getLineFormat().getFillFormat().setFillType(FillType.Solid);
>              autoShape.getLineFormat().getFillFormat().getSolidFillColor().setColor(Color.black);
>          }
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | シェイプを収集するための Presentation |

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - プレゼンテーションに含まれるすべてのシェイプのコレクション