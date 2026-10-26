---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides para Android via Referência da API Java
description: Objeto imutável que representa propriedades de formatação 3-D efetivas.
type: docs
url: /pt/com.aspose.slides/ithreedformateffectivedata/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Objeto imutável que representa propriedades de formatação 3-D efetivas.

--------------------

Esta interface é usada juntamente com a interface [IThreeDFormat](../../com.aspose.slides/ithreedformat) para retornar valores de formatação efetivos com herança aplicada.
## Métodos

| Método | Descrição |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Retorna a largura de um contorno 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Retorna a altura de um efeito de extrusão. |
| [getDepth()](#getDepth--) | Retorna a profundidade de uma forma 3D. |
| [getBevelTop()](#getBevelTop--) | Retorna o tipo de um bisel superior 3D. |
| [getBevelBottom()](#getBevelBottom--) | Retorna o tipo de um bisel inferior 3D. |
| [getContourColor()](#getContourColor--) | Retorna a cor de um contorno. |
| [getExtrusionColor()](#getExtrusionColor--) | Retorna a cor de uma extrusão. |
| [getCamera()](#getCamera--) | Retorna as configurações de uma câmera. |
| [getLightRig()](#getLightRig--) | Retorna o tipo de uma luz. |
| [getMaterial()](#getMaterial--) | Retorna o tipo de um material. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Retorna a largura de um contorno 3D. Somente leitura double.

**Retorna:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Retorna a altura de um efeito de extrusão. Somente leitura double.

**Retorna:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Retorna a profundidade de uma forma 3D. Somente leitura double.

**Retorna:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

Retorna o tipo de um bisel superior 3D. Somente leitura [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Retorna:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

Retorna o tipo de um bisel inferior 3D. Somente leitura [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Retorna:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Integer getContourColor()
```

Retorna a cor de um contorno. Somente leitura java.lang.Integer.

**Retorna:**
java.lang.Integer
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Integer getExtrusionColor()
```

Retorna a cor de uma extrusão. Somente leitura java.lang.Integer.

**Retorna:**
java.lang.Integer
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

Retorna as configurações de uma câmera. Somente leitura [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Retorna:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

Retorna o tipo de uma luz. Somente leitura [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Retorna:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Retorna o tipo de um material. Somente leitura [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Retorna:**
int