---
title: IThreeDFormat
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa propriedades 3-D.
type: docs
url: /pt/com.aspose.slides/ithreedformat/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

Representa propriedades 3-D.
## Métodos

| Método | Descrição |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Retorna ou define a largura de um contorno 3D. |
| [setContourWidth(double value)](#setContourWidth-double-) | Retorna ou define a largura de um contorno 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Retorna ou define a altura de um efeito de extrusão. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Retorna ou define a altura de um efeito de extrusão. |
| [getDepth()](#getDepth--) | Retorna ou define a profundidade de uma forma 3D. |
| [setDepth(double value)](#setDepth-double-) | Retorna ou define a profundidade de uma forma 3D. |
| [getBevelTop()](#getBevelTop--) | Retorna ou define o tipo de um chanfro superior 3D. |
| [getBevelBottom()](#getBevelBottom--) | Retorna ou define o tipo de um chanfro inferior 3D. |
| [getContourColor()](#getContourColor--) | Retorna ou define a cor de um contorno. |
| [getExtrusionColor()](#getExtrusionColor--) | Retorna ou define a cor de uma extrusão. |
| [getCamera()](#getCamera--) | Retorna ou define as configurações de uma câmera. |
| [getLightRig()](#getLightRig--) | Retorna ou define o tipo de uma luz. |
| [getMaterial()](#getMaterial--) | Retorna ou define o tipo de um material. |
| [setMaterial(int value)](#setMaterial-int-) | Retorna ou define o tipo de um material. |
| [getEffective()](#getEffective--) | Obtém dados de formatação 3-D efetivos com a herança aplicada. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


Retorna ou define a largura de um contorno 3D. Leitura/gravação double.

**Retorna:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```


Retorna ou define a largura de um contorno 3D. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


Retorna ou define a altura de um efeito de extrusão. Leitura/gravação double.

**Retorna:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```


Retorna ou define a altura de um efeito de extrusão. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


Retorna ou define a profundidade de uma forma 3D. Leitura/gravação double.

**Retorna:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```


Retorna ou define a profundidade de uma forma 3D. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```


Retorna ou define o tipo de um chanfro superior 3D. Somente leitura [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Retorna:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```


Retorna ou define o tipo de um chanfro inferior 3D. Somente leitura [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Retorna:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```


Retorna ou define a cor de um contorno. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```


Retorna ou define a cor de uma extrusão. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```


Retorna ou define as configurações de uma câmera. Somente leitura [ICamera](../../com.aspose.slides/icamera).

**Retorna:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```


Retorna ou define o tipo de uma luz. Somente leitura [ILightRig](../../com.aspose.slides/ilightrig).

**Retorna:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


Retorna ou define o tipo de um material. Leitura/gravação [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Retorna:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```


Retorna ou define o tipo de um material. Leitura/gravação [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```


Obtém dados de formatação 3-D efetivos com a herança aplicada.

**Retorna:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).