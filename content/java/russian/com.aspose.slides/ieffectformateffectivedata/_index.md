---
title: IEffectFormatEffectiveData
second_title: Справочник API Aspose.Slides для Java
description: Неизменяемый объект, содержащий свойства эффективного форматирования эффектов.
type: docs
url: /ru/com.aspose.slides/ieffectformateffectivedata/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormatEffectiveData extends IEffectParamSource
```

Неизменяемый объект, содержащий свойства эффективного форматирования эффектов.

--------------------

Этот интерфейс используется вместе с интерфейсом [IEffectFormat](../../com.aspose.slides/ieffectformat) для возвращения эффективных значений форматирования с применённым наследованием.
## Методы

| Метод | Описание |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Returns true if all effects are disabled (as just created, default EffectFormat object). |
| [getBlurEffect()](#getBlurEffect--) | Blur effect. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Fill overlay effect. |
| [getGlowEffect()](#getGlowEffect--) | Glow effect. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | Inner shadow. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Outer shadow. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Preset shadow. |
| [getReflectionEffect()](#getReflectionEffect--) | Reflection. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Soft edge. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```


Возвращает true, если все эффекты отключены (как только что созданный объект EffectFormat по умолчанию). Только для чтения boolean.

**Возвращает:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlurEffectiveData getBlurEffect()
```


Эффект размытия. Только для чтения [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).

**Возвращает:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata)
### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlayEffectiveData getFillOverlayEffect()
```


Эффект наложения заливки. Только для чтения [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).

**Возвращает:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata)
### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlowEffectiveData getGlowEffect()
```


Эффект свечения. Только для чтения [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).

**Возвращает:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata)
### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadowEffectiveData getInnerShadowEffect()
```


Внутренняя тень. Только для чтения [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata).

**Возвращает:**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata)
### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadowEffectiveData getOuterShadowEffect()
```


Внешняя тень. Только для чтения [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata).

**Возвращает:**
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata)
### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadowEffectiveData getPresetShadowEffect()
```


Предустановленная тень. Только для чтения [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).

**Возвращает:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata)
### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflectionEffectiveData getReflectionEffect()
```


Отражение. Только для чтения [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata).

**Возвращает:**
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata)
### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdgeEffectiveData getSoftEdgeEffect()
```


Мягкий край. Только для чтения [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).

**Возвращает:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata)