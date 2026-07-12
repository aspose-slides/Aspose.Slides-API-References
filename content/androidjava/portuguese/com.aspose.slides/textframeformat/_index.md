---
title: TextFrameFormat
second_title: Aspose.Slides para Android via Referência da API Java
description: Contém as propriedades formatTextFrameFormatting dos TextFrames.
type: docs
url: /pt/com.aspose.slides/textframeformat/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

Contém as propriedades formatTextFrameFormatting do TextFrame.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | Inicializa uma nova instância da classe [TextFrameFormat](../../com.aspose.slides/textframeformat). |
## Métodos

| Método | Descrição |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | Retorna o estilo do texto. |
| [getThreeDFormat()](#getThreeDFormat--) | Retorna o objeto ThreeDFormat que representa as propriedades de efeito 3d para um texto. |
| [getMarginLeft()](#getMarginLeft--) | Retorna ou define a margem esquerda (pontos) em um TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Retorna ou define a margem esquerda (pontos) em um TextFrame. |
| [getMarginRight()](#getMarginRight--) | Retorna ou define a margem direita (pontos) em um TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Retorna ou define a margem direita (pontos) em um TextFrame. |
| [getMarginTop()](#getMarginTop--) | Retorna ou define a margem superior (pontos) em um TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Retorna ou define a margem superior (pontos) em um TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Retorna ou define a margem inferior (pontos) em um TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Retorna ou define a margem inferior (pontos) em um TextFrame. |
| [getWrapText()](#getWrapText--) | Verdadeiro se o texto estiver envolvido nas margens do TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Verdadeiro se o texto estiver envolvido nas margens do TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Retorna ou define o texto de âncora vertical em um TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Retorna ou define o texto de âncora vertical em um TextFrame. |
| [getCenterText()](#getCenterText--) | Se NullableBool.True então o texto deve ser centralizado horizontalmente na caixa. |
| [setCenterText(byte value)](#setCenterText-byte-) | Se NullableBool.True então o texto deve ser centralizado horizontalmente na caixa. |
| [getTextVerticalType()](#getTextVerticalType--) | Determina a orientação do texto. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Determina a orientação do texto. |
| [getAutofitType()](#getAutofitType--) | Retorna ou define o modo autofit do texto. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Retorna ou define o modo autofit do texto. |
| [getColumnCount()](#getColumnCount--) | Retorna ou define o número de colunas na área de texto. |
| [setColumnCount(int value)](#setColumnCount-int-) | Retorna ou define o número de colunas na área de texto. |
| [getColumnSpacing()](#getColumnSpacing--) | Retorna ou define o espaço entre colunas de texto na área de texto (em pontos). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Retorna ou define o espaço entre colunas de texto na área de texto (em pontos). |
| [getRotationAngle()](#getRotationAngle--) | Especifica a rotação personalizada que está sendo aplicada ao texto dentro da caixa delimitadora. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Especifica a rotação personalizada que está sendo aplicada ao texto dentro da caixa delimitadora. |
| [getTransform()](#getTransform--) | Obtém ou define a forma de quebra de linha do texto. |
| [setTransform(byte value)](#setTransform-byte-) | Obtém ou define a forma de quebra de linha do texto. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Obtém ou define a manutenção do texto plano mesmo se um efeito de Rotação 3-D for aplicado. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Obtém ou define a manutenção do texto plano mesmo se um efeito de Rotação 3-D for aplicado. |
| [getEffective()](#getEffective--) | Obtém os dados de formatação efetiva do quadro de texto com a herança aplicada. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

Inicializa uma nova instância da classe [TextFrameFormat](../../com.aspose.slides/textframeformat).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versão. Somente leitura long.

**Retorna:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

Retorna o estilo do texto. Somente leitura [ITextStyle](../../com.aspose.slides/itextstyle).

**Retorna:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```

Retorna o objeto ThreeDFormat que representa as propriedades de efeito 3d para um texto. Somente leitura [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Definir transformação do texto
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Definir extrusão
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Definir contorno
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Definir profundidade
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Definir material
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Definir iluminação
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Definir tipo de câmera
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Retorna ou define a margem esquerda (pontos) em um TextFrame. Leitura/gravação double.

**Retorna:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Retorna ou define a margem esquerda (pontos) em um TextFrame. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Retorna ou define a margem direita (pontos) em um TextFrame. Leitura/gravação double.

**Retorna:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Retorna ou define a margem direita (pontos) em um TextFrame. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Retorna ou define a margem superior (pontos) em um TextFrame. Leitura/gravação double.

**Retorna:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Retorna ou define a margem superior (pontos) em um TextFrame. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Retorna ou define a margem inferior (pontos) em um TextFrame. Leitura/gravação double.

**Retorna:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Retorna ou define a margem inferior (pontos) em um TextFrame. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

Verdadeiro se o texto estiver envolvido nas margens do TextFrame. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```

Verdadeiro se o texto estiver envolvido nas margens do TextFrame. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```

Retorna ou define o texto de âncora vertical em um TextFrame. Leitura/gravação [TextAnchorType](../../com.aspose.slides/textanchortype).

**Retorna:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

Retorna ou define o texto de âncora vertical em um TextFrame. Leitura/gravação [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

Se NullableBool.True então o texto deve ser centralizado horizontalmente na caixa. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

Se NullableBool.True então o texto deve ser centralizado horizontalmente na caixa. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Determina a orientação do texto. O valor resultante da rotação visual do texto resumido a partir desta propriedade e do ângulo personalizado na propriedade RotationAngle. Leitura/gravação [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Retorna:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Determina a orientação do texto. O valor resultante da rotação visual do texto resumido a partir desta propriedade e do ângulo personalizado na propriedade RotationAngle. Leitura/gravação [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

Retorna ou define o modo autofit do texto. Leitura/gravação [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```

Retorna ou define o modo autofit do texto. Leitura/gravação [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

Retorna ou define o número de colunas na área de texto. Este valor deve ser um número positivo. Caso contrário, o valor será definido como zero. Valor 0 significa valor indefinido. Leitura/gravação int.

--------------------

> ```
> O código de exemplo a seguir mostra como adicionar coluna em um TextFrame dentro de uma apresentação PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```

Retorna ou define o número de colunas na área de texto. Este valor deve ser um número positivo. Caso contrário, o valor será definido como zero. Valor 0 significa valor indefinido. Leitura/gravação int.

--------------------

> ```
> O código de exemplo a seguir mostra como adicionar coluna em Text frame dentro de uma apresentação PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```

Retorna ou define o espaço entre colunas de texto na área de texto (em pontos). Isso só deve ser aplicado quando houver mais de 1 coluna presente. Este valor deve ser um número positivo. Caso contrário, o valor será definido como zero. Leitura/gravação double.

**Retorna:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

Retorna ou define o espaço entre colunas de texto na área de texto (em pontos). Isso só deve ser aplicado quando houver mais de 1 coluna presente. Este valor deve ser um número positivo. Caso contrário, o valor será definido como zero. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

Especifica a rotação personalizada que está sendo aplicada ao texto dentro da caixa delimitadora. Se não for especificado, a rotação da forma acompanhante será usada. Se for especificado, então isto será aplicado independentemente da forma. Ou seja, a forma pode ter uma rotação aplicada além da rotação aplicada ao texto. O valor resultante da rotação visual do texto resumido a partir desta propriedade e do tipo vertical pré-definido na propriedade TextVerticalType. Leitura/gravação float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Retorna:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

Especifica a rotação personalizada que está sendo aplicada ao texto dentro da caixa delimitadora. Se não for especificado, a rotação da forma acompanhante será usada. Se for especificado, então isto será aplicado independentemente da forma. Ou seja, a forma pode ter uma rotação aplicada além da rotação aplicada ao texto. O valor resultante da rotação visual do texto resumido a partir desta propriedade e do tipo vertical pré-definido na propriedade TextVerticalType. Leitura/gravação float.

--------------------

> ```
> Considere o caso em que uma forma tem uma rotação de 90 graus no sentido horário aplicada a ela. 
>  Além disso, o corpo do texto em si tem uma rotação de -90 graus 
>  no sentido anti-horário aplicada a ele. Então a forma resultante pareceria
>  estar rotacionada, mas o texto dentro dela pareceria como se não tivesse sido rotacionado.
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public final byte getTransform()
```

Obtém ou define a forma de quebra de linha do texto. Leitura/gravação [TextShapeType](../../com.aspose.slides/textshapetype).

**Retorna:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

Obtém ou define a forma de quebra de linha do texto. Leitura/gravação [TextShapeType](../../com.aspose.slides/textshapetype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

Obtém ou define a manutenção do texto plano mesmo se um efeito de Rotação 3-D for aplicado. Leitura/gravação boolean.

**Retorna:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```

Obtém ou define a manutenção do texto plano mesmo se um efeito de Rotação 3-D for aplicado. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```

Obtém os dados de formatação efetiva do quadro de texto com a herança aplicada.

--------------------

> ```
> This example demonstrates getting some of effective text frame formatting properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextFrameFormatEffectiveData effectiveTextFrameFormat = shape.getTextFrame().getTextFrameFormat().getEffective();
>     
>      System.out.println("Anchoring type: " + effectiveTextFrameFormat.getAnchoringType());
>      System.out.println("Autofit type: " + effectiveTextFrameFormat.getAutofitType());
>      System.out.println("Text vertical type: " + effectiveTextFrameFormat.getTextVerticalType());
>      System.out.println("Margins");
>      System.out.println("   Left: " + effectiveTextFrameFormat.getMarginLeft());
>      System.out.println("   Top: " + effectiveTextFrameFormat.getMarginTop());
>      System.out.println("   Right: " + effectiveTextFrameFormat.getMarginRight());
>      System.out.println("   Bottom: " + effectiveTextFrameFormat.getMarginBottom());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - Um [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).