---
title: Ink
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um objeto de tinta em um slide.
type: docs
url: /pt/com.aspose.slides/ink/
---
**Herança:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

Representa um objeto de tinta em um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getTraces()](#getTraces--) | Obtém todos os traços contidos no elemento IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
| [getInkEffectImages()](#getInkEffectImages--) | Obtém a coleção de imagens personalizadas usadas para simular efeitos visuais para pincéis de tinta. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```


Obtém todos os traços contidos no elemento IInk [IInkTrace](../../com.aspose.slides/iinktrace). Somente leitura.

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

**Retorna:**
com.aspose.slides.IInkTrace[]
### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```


Obtém a coleção de imagens personalizadas usadas para simular efeitos visuais para pincéis de tinta. Estas imagens são usadas ao renderizar tinta com valores específicos [InkEffectType](../../com.aspose.slides/inkeffecttype), como Galaxy, Rainbow, etc. Ao fornecer suas próprias imagens, você pode controlar como cada efeito de tinta aparece.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```

--------------------

Esta propriedade permite substituir as texturas padrão de efeitos de tinta por texturas definidas pelo usuário, o que é particularmente útil quando os recursos padrão são restritos por licenciamento ou indisponíveis em tempo de execução. Cada entrada no dicionário deve associar um valor [InkEffectType](../../com.aspose.slides/inkeffecttype) a um objeto [IImage](../../com.aspose.slides/iimage) correspondente (por exemplo, Bitmap ou uma interface de imagem Aspose).

**Retorna:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>