---
title: Ink
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: スライド上のインクオブジェクトを表します。
type: docs
url: /ja/com.aspose.slides/ink/
---
**継承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IInk](../../com.aspose.slides/iink)  
```
public class Ink extends GraphicalObject implements IInk
```

スライド上のインクオブジェクトを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTraces()](#getTraces--) | IInk 要素 [IInkTrace](../../com.aspose.slides/iinktrace) に含まれるすべてのトレースを取得します。 |
| [getInkEffectImages()](#getInkEffectImages--) | インクブラシの視覚効果をシミュレートするために使用されるカスタム画像のコレクションを取得します。 |

### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```

IInk 要素 [IInkTrace](../../com.aspose.slides/iinktrace) に含まれるすべてのトレースを取得します。読み取り専用。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**  
com.aspose.slides.IInkTrace[]

### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```

インクブラシの視覚効果をシミュレートするために使用されるカスタム画像のコレクションを取得します。これらの画像は、Galaxy、Rainbow などの特定の [InkEffectType](../../com.aspose.slides/inkeffecttype) 値でインクをレンダリングする際に使用されます。独自の画像を提供することで、各インク効果の表示方法を制御できます。

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```


--------------------

このプロパティは、デフォルトのインク効果テクスチャをユーザー定義のものに置き換えることを可能にします。これは、デフォルトのアセットがライセンスにより制限されている場合や実行時に利用できない場合に特に有用です。辞書の各エントリは、[InkEffectType](../../com.aspose.slides/inkeffecttype) 値と対応する [IImage](../../com.aspose.slides/iimage) オブジェクト（例: Bitmap、または Aspose の画像インターフェイス）を関連付ける必要があります。

**戻り値:**  
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>