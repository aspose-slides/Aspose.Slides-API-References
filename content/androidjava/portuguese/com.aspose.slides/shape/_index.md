---
title: Shape
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa uma forma em um slide.
type: docs
url: /pt/com.aspose.slides/shape/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject
```
public class Shape implements IShape, IDOMObject
```

Representa uma forma em um slide.

## Métodos

| Método | Descrição |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Determina se a forma é TextHolder\_PPT. |
| [getPlaceholder()](#getPlaceholder--) | Retorna o placeholder de uma forma. |
| [removePlaceholder()](#removePlaceholder--) | Define que esta forma não é um placeholder. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Retorna uma forma placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada). |
| [getCustomData()](#getCustomData--) | Retorna os dados personalizados da forma. |
| [getRawFrame()](#getRawFrame--) | Retorna ou define as propriedades da moldura bruta da forma. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Retorna ou define as propriedades da moldura bruta da forma. |
| [getFrame()](#getFrame--) | Retorna ou define as propriedades da moldura da forma. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Retorna ou define as propriedades da moldura da forma. |
| [getLineFormat()](#getLineFormat--) | Retorna o objeto LineFormat que contém propriedades de formatação de linha para uma forma. |
| [getThreeDFormat()](#getThreeDFormat--) | Retorna o objeto ThreeDFormat que contém propriedades de efeito 3d para uma forma. |
| [getEffectFormat()](#getEffectFormat--) | Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a uma forma. |
| [getFillFormat()](#getFillFormat--) | Retorna o objeto FillFormat que contém propriedades de formatação de preenchimento para uma forma. |
| [getImage()](#getImage--) | Retorna a miniatura da forma. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Retorna a miniatura da forma. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Salva o conteúdo da Shape como arquivo SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Salva o conteúdo da Shape como arquivo SVG. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Retorna ou define o hyperlink definido para clique do mouse. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Retorna ou define o hyperlink definido para clique do mouse. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Retorna ou define o hyperlink definido para mouse over. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Retorna ou define o hyperlink definido para mouse over. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Retorna o gerenciador de hyperlink. |
| [getHidden()](#getHidden--) | Determina se a forma está oculta. |
| [setHidden(boolean value)](#setHidden-boolean-) | Determina se a forma está oculta. |
| [getZOrderPosition()](#getZOrderPosition--) | Retorna a posição de uma forma na ordem Z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Retorna o número de pontos de conexão na forma. |
| [getRotation()](#getRotation--) | Retorna ou define o número de graus que a forma especificada está rotacionada ao redor do eixo Z. |
| [setRotation(float value)](#setRotation-float-) | Retorna ou define o número de graus que a forma especificada está rotacionada ao redor do eixo Z. |
| [getX()](#getX--) | Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos. |
| [setX(float value)](#setX-float-) | Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos. |
| [getY()](#getY--) | Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos. |
| [setY(float value)](#setY-float-) | Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos. |
| [getWidth()](#getWidth--) | Obtém ou define a largura da forma, medida em pontos. |
| [setWidth(float value)](#setWidth-float-) | Obtém ou define a largura da forma, medida em pontos. |
| [getHeight()](#getHeight--) | Obtém ou define a altura da forma, medida em pontos. |
| [setHeight(float value)](#setHeight-float-) | Obtém ou define a altura da forma, medida em pontos. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Propriedade especifica como uma forma será renderizada no modo de exibição preto-e-branco. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Propriedade especifica como uma forma será renderizada no modo de exibição preto-e-branco. |
| [getUniqueId()](#getUniqueId--) | Retorna um identificador interno, de escopo de apresentação, destinado ao uso por complementos ou outro código. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Retorna um identificador único de escopo de slide que permanece constante durante a vida útil da forma e permite que o PowerPoint ou código interop referencie a forma de forma confiável a partir de qualquer ponto do documento. |
| [getAlternativeText()](#getAlternativeText--) | Retorna ou define o texto alternativo associado a uma forma. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Retorna ou define o texto alternativo associado a uma forma. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Retorna ou define o título do texto alternativo associado a uma forma. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Retorna ou define o título do texto alternativo associado a uma forma. |
| [getName()](#getName--) | Retorna ou define o nome de uma forma. |
| [setName(String value)](#setName-java.lang.String-) | Retorna ou define o nome de uma forma. |
| [isDecorative()](#isDecorative--) | Obtém ou define a opção “Marcar como decorativo” boolean de leitura/gravação. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Obtém ou define a opção “Marcar como decorativo” boolean de leitura/gravação. |
| [getShapeLock()](#getShapeLock--) | Retorna os bloqueios da forma. |
| [isGrouped()](#isGrouped--) | Determina se a forma está agrupada. |
| [getParentGroup()](#getParentGroup--) | Retorna o objeto GroupShape pai se a forma estiver agrupada. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | Obtém os limites visuais da forma calculados a partir do seu conteúdo renderizado. |
| [getSlide()](#getSlide--) | Retorna o slide pai de uma forma. |
| [getPresentation()](#getPresentation--) | Retorna a apresentação pai de um slide. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

Determina se a forma é TextHolder\_PPT. Somente leitura boolean.

**Retorna:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

Retorna o placeholder de uma forma. Retorna null se a forma não tem placeholder. Somente leitura [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Instancia a classe Presentation
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // Acessa o primeiro slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Itera através das shapes para encontrar o placeholder
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // Altera o texto em cada placeholder
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // Salva a apresentação no disco
>      pres.save("output_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set Prompt Text in Placeholder.
>  
>  Presentation pres = new Presentation("Presentation2.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      for (IShape shape : slide.getSlide().getShapes()) // Itera através do slide
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint exibe "Clique para adicionar título"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Adiciona subtítulo
>              {
>                  text = "Add Subtitle";
>              }
>              ((IAutoShape)shape).getTextFrame().setText(text);
>              System.out.println("Placeholder with text: " + text);
>          }
>      }
>      pres.save("Placeholders_PromptText.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

Define que esta forma não é um placeholder.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder do qual copiar o conteúdo. |

**Retorna:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Novo #getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

Retorna uma forma placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada).

--------------------

> ```
> // obtém todos os efeitos animados (master/layout/slide) da forma placeholder
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape = slide.getShapes().get_Item(0);
>      IEffect[] shapeEffects = slide.getTimeline().getMainSequence().getEffectsByShape(shape);
>      IShape layoutShape = shape.getBasePlaceholder();
>      IEffect[] layoutShapeEffects = slide.getLayoutSlide().getTimeline().getMainSequence().getEffectsByShape(layoutShape);
>      IShape masterShape = layoutShape.getBasePlaceholder();
>      IEffect[] masterShapeEffects = slide.getLayoutSlide().getMasterSlide().getTimeline().getMainSequence().getEffectsByShape(masterShape);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

A null é retornada se a forma atual não for herdada.

**Retorna:**
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Retorna os dados personalizados da forma. Somente leitura [ICustomData](../../com.aspose.slides/icustomdata).

**Retorna:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

Retorna ou define as propriedades da moldura bruta da forma. Leitura/Escrita [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //ou
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Tal código pode levar a situações ambíguas. Portanto, foram adicionadas restrições para o uso de valores indefinidos em IShape.getFrame(). Os valores de x, y, width, height, flipH, flipV e rotationAngle devem ser definidos (não Float.NaN ou NullableBool.NotDefined). O código de exemplo acima agora lança a exceção ArgumentException.
>  //Isto se aplica a estes casos de uso:
>  IShape shape = ...;
>  shape.setFrame(...); // não pode ser indefinido
>  IShapeCollection shapes = ...;
>  // os parâmetros x, y, width, height não podem ser Float.NaN:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  //Mas as propriedades de frame de IShape.RawFrame podem ser indefinidas. Isso faz sentido quando a forma está vinculada a um placeholder. Então, os valores indefinidos do frame da forma são sobrescritos a partir da forma placeholder pai. Se não houver forma placeholder pai para essa forma, então ela usa valores padrão ao avaliar o frame efetivo com base em IShape.RawFrame. Os valores padrão são 0 e NullableBool.False para x, y, width, height, flipH, flipV e rotationAngle. Por exemplo:
>  IShape shape = ...; // forma está vinculada ao placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // agora a forma herda os valores x, y, height, flipH, flipV do placeholder e sobrescreve width=100 e rotationAngle=0.{code}
> ```


**Retorna:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

Retorna ou define as propriedades da moldura bruta da forma. Leitura/Escrita [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //ou
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Tal código pode levar a situações ambíguas. Portanto, foram adicionadas restrições para o uso de valores indefinidos em IShape.getFrame(). Os valores de x, y, width, height, flipH, flipV e rotationAngle devem ser definidos (não Float.NaN ou NullableBool.NotDefined). O código de exemplo acima agora lança a exceção ArgumentException.
>  //Isto se aplica a estes casos de uso:
>  IShape shape = ...;
>  shape.setFrame(...); // não pode ser indefinido
>  IShapeCollection shapes = ...;
>  // os parâmetros x, y, width, height não podem ser Float.NaN:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  //Mas as propriedades de frame de IShape.RawFrame podem ser indefinidas. Isso faz sentido quando a forma está vinculada a um placeholder. Então, os valores indefinidos do frame da forma são sobrescritos a partir da forma placeholder pai. Se não houver forma placeholder pai para essa forma, então ela usa valores padrão ao avaliar o frame efetivo com base em IShape.RawFrame. Os valores padrão são 0 e NullableBool.False para x, y, width, height, flipH, flipV e rotationAngle. Por exemplo:
>  IShape shape = ...; // a forma está vinculada ao placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // agora a forma herda os valores x, y, height, flipH, flipV do placeholder e sobrescreve width=100 e rotationAngle=0.{code}
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Retorna ou define as propriedades da moldura da forma. Leitura/Escrita [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

O valor de cada propriedade da instância IShapeFrame retornada não é indefinido (não é NaN nem NotDefined). O valor de cada propriedade da instância IShapeFrame atribuída deve ser definido (não NaN nem NotDefined). É possível definir valores indefinidos para propriedades da instância RawFrame.

**Retorna:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Retorna ou define as propriedades da moldura da forma. Leitura/Escrita [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

O valor de cada propriedade da instância IShapeFrame retornada não é indefinido (não é NaN nem NotDefined). O valor de cada propriedade da instância IShapeFrame atribuída deve ser definido (não NaN nem NotDefined). É possível definir valores indefinidos para propriedades da instância RawFrame.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Retorna o objeto LineFormat que contém propriedades de formatação de linha para uma forma. Observação: pode retornar null para certos tipos de formas que não possuem propriedades de linha. Somente leitura [ILineFormat](../../com.aspose.slides/ilineformat).

**Retorna:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

Retorna o objeto ThreeDFormat que contém propriedades de efeito 3d para uma forma. Observação: pode retornar null para certos tipos de formas que não possuem propriedades 3d. Somente leitura [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Retorna:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a uma forma. Observação: pode retornar null para certos tipos de formas que não possuem propriedades de efeito. Somente leitura [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Retorna:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Retorna o objeto FillFormat que contém propriedades de formatação de preenchimento para uma forma. Observação: pode retornar null para certos tipos de formas que não possuem propriedades de preenchimento. Somente leitura [IFillFormat](../../com.aspose.slides/ifillformat).

--------------------

> ```
> The following example shows how to change the accent color for a theme of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      shape.getFillFormat().setFillType(FillType.Solid);
>      shape.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example demonstrates how to obtain palette colors from the main theme color and then used in shapes.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Accent 4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // Accent 4, Mais claro 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Accent 4, Mais claro 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Accent 4, Mais claro 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Accent 4, Mais escuro 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Accent 4, Mais escuro 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

Retorna a miniatura da forma. ShapeThumbnailBounds.Shape é o tipo de limites de miniatura usado por padrão.

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Miniatura da forma.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

Retorna a miniatura da forma.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bounds | int | Tipo de limites da miniatura da forma. |
| scaleX | float | Escala X |
| scaleY | float | Escala Y |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Miniatura da forma ou null caso ShapeThumbnailBounds.Appearance seja usado e a forma não possua elementos visíveis.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Salva o conteúdo da Shape como arquivo SVG.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream de destino |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Salva o conteúdo da Shape como arquivo SVG.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream de destino |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opções de geração SVG |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Retorna ou define o hyperlink definido para clique do mouse. Leitura/Escrita [IHyperlink](../../com.aspose.slides/ihyperlink).

**Retorna:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Retorna ou define o hyperlink definido para clique do mouse. Leitura/Escrita [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Retorna ou define o hyperlink definido para mouse over. Leitura/Escrita [IHyperlink](../../com.aspose.slides/ihyperlink).

**Retorna:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Retorna ou define o hyperlink definido para mouse over. Leitura/Escrita [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Retorna o gerenciador de hyperlink. Somente leitura [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Retorna:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Determina se a forma está oculta. Leitura/Escrita boolean.

**Retorna:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Determina se a forma está oculta. Leitura/Escrita boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

Retorna a posição de uma forma na ordem Z. Shapes[0] retorna a forma no fundo da ordem Z, e Shapes[Shapes.Count - 1] retorna a forma na frente da ordem Z. Somente leitura int.

**Retorna:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

Retorna o número de pontos de conexão na forma. Somente leitura int.

**Retorna:**
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Retorna ou define o número de graus que a forma especificada está rotacionada ao redor do eixo Z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Leitura/Escrita float.

--------------------

O valor retornado é sempre definido (não é Float.NaN). O valor atribuído deve ser definido (não Float.NaN). É possível definir valores indefinidos para propriedades da instância RawFrame.

**Retorna:**
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```

Retorna ou define o número de graus que a forma especificada está rotacionada ao redor do eixo Z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Leitura/Escrita float.

--------------------

O valor retornado é sempre definido (não é Float.NaN). O valor atribuído deve ser definido (não Float.NaN). É possível definir valores indefinidos para propriedades da instância RawFrame.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos. Leitura/Escrita float.

--------------------

O valor retornado é sempre definido e nunca Float.NaN. O valor atribuído também deve ser definido; atribua Float.NaN apenas a propriedades de uma instância RawFrame.

**Retorna:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos. Leitura/Escrita float.

--------------------

O valor retornado é sempre definido e nunca Float.NaN. O valor atribuído também deve ser definido; atribua Float.NaN apenas a propriedades de uma instância RawFrame.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos. Leitura/Escrita float.

--------------------

O valor retornado é sempre definido e nunca Float.NaN. O valor atribuído também deve ser definido; atribua Float.NaN apenas a propriedades de uma instância RawFrame.

**Retorna:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos. Leitura/Escrita float.

--------------------

O valor retornado é sempre definido e nunca Float.NaN. O valor atribuído também deve ser definido; atribua Float.NaN apenas a propriedades de uma instância RawFrame.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Obtém ou define a largura da forma, medida em pontos. Leitura/Escrita float.

--------------------

O valor retornado é sempre definido e nunca Float.NaN. O valor atribuído também deve ser definido; atribua Float.NaN apenas a propriedades de uma instância RawFrame.

**Retorna:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Obtém ou define a largura da forma, medida em pontos. Leitura/Escrita float.

--------------------

O valor retornado é sempre definido e nunca Float.NaN. O valor atribuído também deve ser definido; atribua Float.NaN apenas a propriedades de uma instância RawFrame.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Obtém ou define a altura da forma, medida em pontos. Leitura/Escrita float.

--------------------

O valor retornado é sempre definido e nunca Float.NaN. O valor atribuído também deve ser definido; atribua Float.NaN apenas a propriedades de uma instância RawFrame.

**Retorna:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Obtém ou define a altura da forma, medida em pontos. Leitura/Escrita float.

--------------------

O valor retornado é sempre definido e nunca Float.NaN. O valor atribuído também deve ser definido; atribua Float.NaN apenas a propriedades de uma instância RawFrame.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

Propriedade especifica como uma forma será renderizada no modo de exibição preto-e-branco. Leitura/Escrita [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Retorna:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

Propriedade especifica como uma forma será renderizada no modo de exibição preto-e-branco. Leitura/Escrita [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

Retorna um identificador interno, de escopo de apresentação, destinado ao uso por complementos ou outro código. Como este valor pode ser reatribuído pelo usuário ou programaticamente, ele não deve ser tratado como uma chave única persistente. Somente leitura long. Veja também \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Retorna:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

Retorna um identificador único de escopo de slide que permanece constante durante a vida útil da forma e permite que o PowerPoint ou código interop referencie a forma de forma confiável a partir de qualquer ponto do documento. Somente leitura long. Veja também \#getUniqueId.getUniqueId.

**Retorna:**
long

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

Retorna ou define o texto alternativo associado a uma forma. Leitura/Escrita String.

**Retorna:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

Retorna ou define o texto alternativo associado a uma forma. Leitura/Escrita String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

Retorna ou define o título do texto alternativo associado a uma forma. Leitura/Escrita String.

**Retorna:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

Retorna ou define o título do texto alternativo associado a uma forma. Leitura/Escrita String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

Retorna ou define o nome de uma forma. Deve ser não nulo. Use string vazia se necessário. Leitura/Escrita String.

**Retorna:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Retorna ou define o nome de uma forma. Deve ser não nulo. Use string vazia se necessário. Leitura/Escrita String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

Obtém ou define a opção “Marcar como decorativo” boolean de leitura/gravação.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
boolean

### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```

Obtém ou define a opção “Marcar como decorativo” boolean de leitura/gravação.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```

Retorna os bloqueios da forma. Somente leitura [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Retorna:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

Determina se a forma está agrupada. Somente leitura boolean.

--------------------

A propriedade \#getParentGroup.getParentGroup retorna o objeto GroupShape pai se a forma estiver agrupada.

**Retorna:**
boolean

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Retorna o objeto GroupShape pai se a forma estiver agrupada. Caso contrário, retorna null. Somente leitura [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

A propriedade \#isGrouped.isGrouped determina se a forma está agrupada.

**Retorna:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent\_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject

### getVisualBounds() {#getVisualBounds--}
```
public final RectF getVisualBounds()
```

Obtém os limites visuais da forma calculados a partir do seu conteúdo renderizado.

**Retorna:**
android.graphics.RectF - Um android.graphics.RectF que representa os limites visuais da forma em coordenadas do slide.

--------------------

 O retângulo retornado representa os limites alinhados ao eixo de todo o conteúdo produzido pela forma durante a renderização no espaço de coordenadas do slide. Esses limites podem diferir dos limites de modelo da forma \#getX.getX/\#setX(float).setX(float), \#getY.getY/\#setY(float).setY(float), \#getWidth.getWidth/\#setWidth(float).setWidth(float), \#getHeight.getHeight/\#setHeight(float).setHeight(float) e podem conter coordenadas negativas se o conteúdo renderizado se estender além da origem do slide. Os limites visuais consideram aspectos relacionados à renderização, como transformações (por exemplo, rotação), largura e junções de traço, layout e transbordamento de texto, geometria de SmartArt e outros efeitos de layout que influenciam a aparência final renderizada da forma. Os limites retornados não são recortados ao retângulo do slide.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retorna o slide pai de uma forma. Somente leitura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Retorna:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retorna a apresentação pai de um slide. Somente leitura [IPresentation](../../com.aspose.slides/ipresentation).

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation)