---
title: IThreeDFormat
second_title: Referência da API Aspose.Slides para Java
description: Representa propriedades 3-D.
type: docs
url: /pt/com.aspose.slides/ithreedformat/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

Representa propriedades 3D.
## Métodos

| Método | Descrição |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Obtém ou define a largura de um contorno 3D. |
| [setContourWidth(double value)](#setContourWidth-double-) | Obtém ou define a largura de um contorno 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Obtém ou define a altura de um efeito de extrusão. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Obtém ou define a altura de um efeito de extrusão. |
| [getDepth()](#getDepth--) | Obtém ou define a profundidade de uma forma 3D. |
| [setDepth(double value)](#setDepth-double-) | Obtém ou define a profundidade de uma forma 3D. |
| [getBevelTop()](#getBevelTop--) | Obtém ou define o tipo de um chanfro superior 3D. |
| [getBevelBottom()](#getBevelBottom--) | Obtém ou define o tipo de um chanfro inferior 3D. |
| [getContourColor()](#getContourColor--) | Obtém ou define a cor de um contorno. |
| [getExtrusionColor()](#getExtrusionColor--) | Obtém ou define a cor de uma extrusão. |
| [getCamera()](#getCamera--) | Obtém ou define as configurações de uma câmera. |
| [getLightRig()](#getLightRig--) | Obtém ou define o tipo de uma luz. |
| [getMaterial()](#getMaterial--) | Obtém ou define o tipo de um material. |
| [setMaterial(int value)](#setMaterial-int-) | Obtém ou define o tipo de um material. |
| [getEffective()](#getEffective--) | Obtém os dados de formatação 3D efetivos com a herança aplicada. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Obtém ou define a largura de um contorno 3D. Leitura/gravação double.

**Retorna:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

Obtém ou define a largura de um contorno 3D. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Obtém ou define a altura de um efeito de extrusão. Leitura/gravação double.

**Retorna:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

Obtém ou define a altura de um efeito de extrusão. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Obtém ou define a profundidade de uma forma 3D. Leitura/gravação double.

**Retorna:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

Obtém ou define a profundidade de uma forma 3D. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

Obtém ou define o tipo de um chanfro superior 3D. Somente leitura [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Retorna:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

Obtém ou define o tipo de um chanfro inferior 3D. Somente leitura [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Retorna:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

Obtém ou define a cor de um contorno. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

Obtém ou define a cor de uma extrusão. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

Obtém ou define as configurações de uma câmera. Somente leitura [ICamera](../../com.aspose.slides/icamera).

**Retorna:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

Obtém ou define o tipo de uma luz. Somente leitura [ILightRig](../../com.aspose.slides/ilightrig).

**Retorna:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Obtém ou define o tipo de um material. Leitura/gravação [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Retorna:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

Obtém ou define o tipo de um material. Leitura/gravação [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

Obtém os dados de formatação 3D efetivos com a herança aplicada.

**Retorna:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).