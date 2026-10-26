---
title: IPresetShadowEffectiveData
second_title: Referência da API Aspose.Slides para Java
description: Objeto imutável que representa um efeito de sombra predefinido.
type: docs
url: /pt/com.aspose.slides/ipresetshadoweffectivedata/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IPresetShadowEffectiveData extends IEffectEffectiveData
```

Objeto imutável que representa um efeito de sombra predefinido.
## Métodos

| Método | Descrição |
| --- | --- |
| [getDirection()](#getDirection--) | Direção da sombra. |
| [getDistance()](#getDistance--) | Distância da sombra. |
| [getShadowColor()](#getShadowColor--) | Cor da sombra. |
| [getPreset()](#getPreset--) | Predefinição. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


Direção da sombra. Somente leitura float.

**Retorna:**
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


Distância da sombra. Somente leitura double.

**Retorna:**
double
### getShadowColor() {#getShadowColor--}
```
public abstract Color getShadowColor()
```


Cor da sombra. Somente leitura java.awt.Color.

**Retorna:**
java.awt.Color
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```


Predefinição. Somente leitura [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Retorna:**
int