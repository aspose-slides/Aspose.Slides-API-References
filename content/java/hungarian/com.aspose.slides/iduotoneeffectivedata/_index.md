---
title: IDuotoneEffectiveData
second_title: Aspose.Slides Java API hivatkozás
description: Módosíthatatlan objektum, amely egy Duotone hatást képvisel.
type: docs
url: /hu/com.aspose.slides/iduotoneeffectivedata/
---
**Összes megvalósított interfész:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Módosíthatatlan objektum, amely egy Duotone hatást reprezentál. Minden pixelhez lineáris interpolációval kombinálja a clr1 és a clr2 értékeket, hogy meghatározza az új színt az adott pixel számára.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getColor1()](#getColor1--) | Visszaadja a sötét pixelek cél színformátumát. |
| [getColor2()](#getColor2--) | Visszaadja a világos pixelek cél színformátumát. |
### getColor1() {#getColor1--}
```
public abstract Color getColor1()
```


Visszaadja a sötét pixelek cél színformátumát. Csak olvasható java.awt.Color.

**Visszatér:**
java.awt.Color
### getColor2() {#getColor2--}
```
public abstract Color getColor2()
```


Visszaadja a világos pixelek cél színformátumát. Csak olvasható java.awt.Color.

**Visszatér:**
java.awt.Color