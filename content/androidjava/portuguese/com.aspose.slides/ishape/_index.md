---
title: IShape
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma shape em um slide.
type: docs
url: /pt/com.aspose.slides/ishape/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

Representa uma shape em um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Determina se a shape é TextHolder. |
| [getPlaceholder()](#getPlaceholder--) | Retorna o placeholder para uma shape. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado. |
| [removePlaceholder()](#removePlaceholder--) | Define que esta shape não é um placeholder. |
| [getCustomData()](#getCustomData--) | Retorna os dados personalizados da shape. |
| [getRawFrame()](#getRawFrame--) | Retorna ou define as propriedades da moldura bruta da shape. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Retorna ou define as propriedades da moldura bruta da shape. |
| [getFrame()](#getFrame--) | Retorna ou define as propriedades da moldura da shape. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Retorna ou define as propriedades da moldura da shape. |
| [getLineFormat()](#getLineFormat--) | Retorna o objeto LineFormat que contém propriedades de formatação de linha para uma shape. |
| [getThreeDFormat()](#getThreeDFormat--) | Retorna o objeto ThreeDFormat que contém propriedades de formatação de linha para uma shape. |
| [getEffectFormat()](#getEffectFormat--) | Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a uma shape. |
| [getFillFormat()](#getFillFormat--) | Retorna o objeto FillFormat que contém propriedades de formatação de preenchimento para uma shape. |
| [getImage()](#getImage--) | Retorna a miniatura da shape. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Retorna a miniatura da shape. |
| [getHidden()](#getHidden--) | Determina se a shape está oculta. |
| [setHidden(boolean value)](#setHidden-boolean-) | Determina se a shape está oculta. |
| [getZOrderPosition()](#getZOrderPosition--) | Retorna a posição de uma shape na ordem Z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Retorna o número de pontos de conexão na shape. |
| [getRotation()](#getRotation--) | Retorna ou define o número de graus que a shape especificada está rotacionada ao redor do eixo Z. |
| [setRotation(float value)](#setRotation-float-) | Retorna ou define o número de graus que a shape especificada está rotacionada ao redor do eixo Z. |
| [getX()](#getX--) | Obtém ou define a coordenada x do canto superior esquerdo da shape, medida em pontos. |
| [setX(float value)](#setX-float-) | Obtém ou define a coordenada x do canto superior esquerdo da shape, medida em pontos. |
| [getY()](#getY--) | Obtém ou define a coordenada y do canto superior esquerdo da shape, medida em pontos. |
| [setY(float value)](#setY-float-) | Obtém ou define a coordenada y do canto superior esquerdo da shape, medida em pontos. |
| [getWidth()](#getWidth--) | Obtém ou define a largura da shape, medida em pontos. |
| [setWidth(float value)](#setWidth-float-) | Obtém ou define a largura da shape, medida em pontos. |
| [getHeight()](#getHeight--) | Obtém ou define a altura da shape, medida em pontos. |
| [setHeight(float value)](#setHeight-float-) | Obtém ou define a altura da shape, medida em pontos. |
| [getAlternativeText()](#getAlternativeText--) | Retorna ou define o texto alternativo associado a uma shape. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Retorna ou define o texto alternativo associado a uma shape. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Retorna ou define o título do texto alternativo associado a uma shape. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Retorna ou define o título do texto alternativo associado a uma shape. |
| [getName()](#getName--) | Retorna ou define o nome de uma shape. |
| [setName(String value)](#setName-java.lang.String-) | Retorna ou define o nome de uma shape. |
| [isDecorative()](#isDecorative--) | Obtém ou define a opção 'Marcar como decorativa' (Somente leitura/gravável) boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Obtém ou define a opção 'Marcar como decorativa' (Somente leitura/gravável) boolean. |
| [getShapeLock()](#getShapeLock--) | Retorna os bloqueios da shape. |
| [getUniqueId()](#getUniqueId--) | Retorna um identificador interno, limitado à apresentação, destinado ao uso por complementos ou outro código. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Retorna um identificador único limitado ao slide que permanece constante durante a vida da shape e permite que o PowerPoint ou código interop a referencie confiavelmente de qualquer ponto do documento. |
| [isGrouped()](#isGrouped--) | Determina se a shape está agrupada. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Propriedade que especifica como uma shape será renderizada no modo de exibição em preto e branco. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Propriedade que especifica como uma shape será renderizada no modo de exibição em preto e branco. |
| [getParentGroup()](#getParentGroup--) | Retorna o objeto GroupShape pai se a shape estiver agrupada. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Salva o conteúdo da Shape como arquivo SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Salva o conteúdo da Shape como arquivo SVG. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Retorna uma shape placeholder básica (shape do layout e/ou mestre que a shape atual herda). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

Determina se a shape é TextHolder. Somente leitura boolean.

**Retorna:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

Retorna o placeholder para uma shape. Somente leitura [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Retorna:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder do qual copiar o conteúdo. |

**Retorna:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Novo [IPlaceholder](../../com.aspose.slides/iplaceholder).

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

Define que esta shape não é um placeholder.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Retorna os dados personalizados da shape. Somente leitura [ICustomData](../../com.aspose.slides/icustomdata).

**Retorna:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

Retorna ou define as propriedades da moldura bruta da shape. Leitura/gravação [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //ou
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Tal código pode levar a situações pouco claras. Portanto, foram adicionadas restrições ao usar valores indefinidos para IShape.getFrame(). Os valores de x, y, width, height, flipH, flipV e rotationAngle devem ser definidos (não Float.NaN ou NullableBool.NotDefined). O código de exemplo acima agora lança a exceção ArgumentException.
>  //Isso se aplica a esses casos de uso:
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape está vinculada ao placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // agora a shape herda os valores de x, y, height, flipH, flipV do placeholder e substitui width=100 e rotationAngle=0.
```

**Retorna:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

Retorna ou define as propriedades da moldura bruta da shape. Leitura/gravação [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //ou
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Tal código pode levar a situações pouco claras. Portanto, foram adicionadas restrições ao usar valores indefinidos para IShape.getFrame(). Os valores de x, y, width, height, flipH, flipV e rotationAngle devem ser definidos (não Float.NaN ou NullableBool.NotDefined). O código de exemplo acima agora lança a exceção ArgumentException.
>  //Isso se aplica a esses casos de uso:
>  IShape shape = ...;
>  shape.setFrame(...); // não pode ser indefinido
>  IShapeCollection shapes = ...;
>  // Os parâmetros x, y, width, height não podem ser Float.NaN:
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape está vinculada ao placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // agora a shape herda x, y, height, flipH, flipV do placeholder e substitui width=100 e rotationAngle=0.
```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Retorna ou define as propriedades da moldura da shape. Leitura/gravação [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

O valor de cada propriedade da instância IShapeFrame retornada não é indefinido (não é NaN nem NotDefined). O valor de cada propriedade da instância IShapeFrame atribuída deve ser definido (não NaN nem NotDefined). Você pode definir valores indefinidos para propriedades da instância RawFrame.

**Retorna:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Retorna ou define as propriedades da moldura da shape. Leitura/gravação [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

O valor de cada propriedade da instância IShapeFrame retornada não é indefinido (não é NaN nem NotDefined). O valor de cada propriedade da instância IShapeFrame atribuída deve ser definido (não NaN nem NotDefined). Você pode definir valores indefinidos para propriedades da instância RawFrame.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Retorna o objeto LineFormat que contém propriedades de formatação de linha para uma shape. Somente leitura [ILineFormat](../../com.aspose.slides/ilineformat).

**Retorna:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Retorna o objeto ThreeDFormat que contém propriedades de formatação de linha para uma shape. Somente leitura [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Retorna:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a uma shape. Somente leitura [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Retorna:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Retorna o objeto FillFormat que contém propriedades de formatação de preenchimento para uma shape. Somente leitura [IFillFormat](../../com.aspose.slides/ifillformat).

**Retorna:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Retorna a miniatura da shape. O tipo ShapeThumbnailBounds.Shape é usado por padrão.

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Miniatura da shape.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

Retorna a miniatura da shape.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bounds | int | Tipo de limites da miniatura da shape. |
| scaleX | float | Escala X |
| scaleY | float | Escala Y |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Miniatura da shape ou null caso o tipo ShapeThumbnailBounds.Appearance seja usado e a shape não possua elementos visíveis.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Determina se a shape está oculta. Leitura/gravação boolean.

**Retorna:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Determina se a shape está oculta. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

Retorna a posição de uma shape na ordem Z. Shapes[0] retorna a shape mais ao fundo da ordem Z, e Shapes[Shapes.Count - 1] retorna a shape mais à frente da ordem Z. Somente leitura int.

**Retorna:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

Retorna o número de pontos de conexão na shape. Somente leitura int.

**Retorna:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Retorna ou define o número de graus que a shape especificada está rotacionada ao redor do eixo Z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Leitura/gravação float.

--------------------

O valor retornado está sempre definido (não é Float.NaN). O valor atribuído deve ser definido (não Float.NaN). Você pode definir valores indefinidos para propriedades da instância RawFrame.

**Retorna:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

Retorna ou define o número de graus que a shape especificada está rotacionada ao redor do eixo Z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Leitura/gravação float.

--------------------

O valor retornado está sempre definido (não é Float.NaN). O valor atribuído deve ser definido (não Float.NaN). Você pode definir valores indefinidos para propriedades da instância RawFrame.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

Obtém ou define a coordenada x do canto superior esquerdo da shape, medida em pontos. Leitura/gravação float.

--------------------

O valor retornado está sempre definido e nunca é Float.NaN. O valor atribuído também deve ser definido; atribua Float.NaN somente a propriedades de uma instância RawFrame.

**Retorna:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

Obtém ou define a coordenada x do canto superior esquerdo da shape, medida em pontos. Leitura/gravação float.

--------------------

O valor retornado está sempre definido e nunca é Float.NaN. O valor atribuído também deve ser definido; atribua Float.NaN somente a propriedades de uma instância RawFrame.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

Obtém ou define a coordenada y do canto superior esquerdo da shape, medida em pontos. Leitura/gravação float.

--------------------

O valor retornado está sempre definido e nunca é Float.NaN. O valor atribuído também deve ser definido; atribua Float.NaN somente a propriedades de uma instância RawFrame.

**Retorna:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

Obtém ou define a coordenada y do canto superior esquerdo da shape, medida em pontos. Leitura/gravação float.

--------------------

O valor retornado está sempre definido e nunca é Float.NaN. O valor atribuído também deve ser definido; atribua Float.NaN somente a propriedades de uma instância RawFrame.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Obtém ou define a largura da shape, medida em pontos. Leitura/gravação float.

--------------------

O valor retornado está sempre definido e nunca é Float.NaN. O valor atribuído também deve ser definido; atribua Float.NaN somente a propriedades de uma instância RawFrame.

**Retorna:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

Obtém ou define a largura da shape, medida em pontos. Leitura/gravação float.

--------------------

O valor retornado está sempre definido e nunca é Float.NaN. O valor atribuído também deve ser definido; atribua Float.NaN somente a propriedades de uma instância RawFrame.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Obtém ou define a altura da shape, medida em pontos. Leitura/gravação float.

--------------------

O valor retornado está sempre definido e nunca é Float.NaN. O valor atribuído também deve ser definido; atribua Float.NaN somente a propriedades de uma instância RawFrame.

**Retorna:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Obtém ou define a altura da shape, medida em pontos. Leitura/gravação float.

--------------------

O valor retornado está sempre definido e nunca é Float.NaN. O valor atribuído também deve ser definido; atribua Float.NaN somente a propriedades de uma instância RawFrame.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

Retorna ou define o texto alternativo associado a uma shape. Leitura/gravação String.

**Retorna:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

Retorna ou define o texto alternativo associado a uma shape. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

Retorna ou define o título do texto alternativo associado a uma shape. Leitura/gravação String.

**Retorna:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

Retorna ou define o título do texto alternativo associado a uma shape. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

Retorna ou define o nome de uma shape. Leitura/gravação String.

**Retorna:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Retorna ou define o nome de uma shape. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

Obtém ou define a opção 'Marcar como decorativa' (Leitura/gravação) boolean.

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
public abstract void setDecorative(boolean value)
```

Obtém ou define a opção 'Marcar como decorativa' (Leitura/gravação) boolean.

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
public abstract IBaseShapeLock getShapeLock()
```

Retorna os bloqueios da shape. Somente leitura [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Retorna:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

Retorna um identificador interno, limitado à apresentação, destinado ao uso por complementos ou outro código. Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado como chave única persistente. Somente leitura long. Veja também \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Retorna:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

Retorna um identificador único limitado ao slide que permanece constante durante a vida da shape e permite que o PowerPoint ou código interop a referencie confiavelmente de qualquer ponto do documento. Somente leitura long. Veja também \#getUniqueId.getUniqueId.

**Retorna:**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

Determina se a shape está agrupada. Somente leitura boolean.

--------------------

A propriedade \#getParentGroup.getParentGroup retorna o objeto GroupShape pai se a shape estiver agrupada.

**Retorna:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

Propriedade que especifica como uma shape será renderizada no modo de exibição em preto e branco. Leitura/gravação [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Retorna:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

Propriedade que especifica como uma shape será renderizada no modo de exibição em preto e branco. Leitura/gravação [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Retorna o objeto GroupShape pai se a shape estiver agrupada. Caso contrário, retorna null. Somente leitura [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

A propriedade \#isGrouped.isGrouped determina se a shape está agrupada.

**Retorna:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Salva o conteúdo da Shape como arquivo SVG.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream de destino |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Salva o conteúdo da Shape como arquivo SVG.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream de destino |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opções de geração SVG |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

Retorna uma shape placeholder básica (shape do layout e/ou mestre que a shape atual herda).

--------------------

> ```
> // obtém todos (master/layout/slide) os efeitos animados da shape placeholder
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

--------------------

Um null é retornado se a shape atual não for herdada.

**Retorna:**
[IShape](../../com.aspose.slides/ishape)