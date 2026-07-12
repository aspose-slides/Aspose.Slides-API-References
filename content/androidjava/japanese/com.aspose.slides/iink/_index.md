---
title: IInk
second_title: Java API リファレンスを使用した Android 用 Aspose.Slides
description: スライド上のインクオブジェクトを表します。
type: docs
url: /ja/com.aspose.slides/iink/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

スライド上のインクオブジェクトを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTraces()](#getTraces--) | IInk要素[IInkTrace](../../com.aspose.slides/iinktrace)に含まれるすべてのトレースを取得します。 |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```

IInk要素[IInkTrace](../../com.aspose.slides/iinktrace)に含まれるすべてのトレースを取得します。読み取り専用です。

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