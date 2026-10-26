---
title: Collect
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um grupo de métodos destinado a coletar objetos de modelo de diferentes tipos de .
type: docs
url: /pt/com.aspose.slides/collect/
---
**Herança:**
java.lang.Object
```
public class Collect
```

Representa um grupo de métodos destinado a coletar objetos de modelo de diferentes tipos de [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... alterar a formatação da forma ou outras propriedades
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Construtores

| Construtor | Descrição |
| --- | --- |
| [Collect()](#Collect--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | Coleta todas as instâncias de [Shape](../../com.aspose.slides/shape) no [Presentation](../../com.aspose.slides/presentation). |
### Collect() {#Collect--}
```
public Collect()
```


### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```


Coleta todas as instâncias de [Shape](../../com.aspose.slides/shape) no [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // se a forma for AutoShape, adicione uma borda sólida preta
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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Apresentação para coletar formas |

**Retorno:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - Coleção de todas as formas que estão contidas na apresentação