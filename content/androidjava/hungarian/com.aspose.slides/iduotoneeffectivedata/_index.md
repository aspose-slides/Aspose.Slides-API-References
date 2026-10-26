---
title: IDuotoneEffectiveData
second_title: Aspose.Slides for Android a Java API Referencián keresztül
description: Módosíthatatlan objektum, amely duotón hatást képvisel.
type: docs
url: /hu/com.aspose.slides/iduotoneeffectivedata/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Módosíthatatlan objektum, amely duotón hatást képvisel. Minden pixelhez lineáris interpolációval kombinálja a clr1-et és a clr2-t, hogy meghatározza az új színt a pixel számára.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getColor1()](#getColor1--) | Visszaadja a cél színformátumot a sötét pixelekhez. |
| [getColor2()](#getColor2--) | Visszaadja a cél színformátumot a világos pixelekhez. |
### getColor1() {#getColor1--}
```
public abstract Integer getColor1()
```

Visszaadja a cél színformátumot a sötét pixelekhez. Csak olvasható java.lang.Integer.

**Visszatér:**  
java.lang.Integer
### getColor2() {#getColor2--}
```
public abstract Integer getColor2()
```

Visszaadja a cél színformátumot a világos pixelekhez. Csak olvasható java.lang.Integer.

**Visszatér:**  
java.lang.Integer