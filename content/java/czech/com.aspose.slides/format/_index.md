---
title: Format
second_title: Referenční příručka API Aspose.Slides pro Javu
description: Reprezentuje vlastnosti formátu grafu.
type: docs
url: /cs/com.aspose.slides/format/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.IFormat](../../com.aspose.slides/iformat)
```
public final class Format extends PVIObject implements IFormat
```

Reprezentuje vlastnosti formátu grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFill()](#getFill--) | Vrací vlastnosti stylu výplně grafu. |
| [getLine()](#getLine--) | Vrací vlastnosti stylu čáry grafu. |
| [getEffect()](#getEffect--) | Vrací efekty použité pro graf. |
| [getEffect3D()](#getEffect3D--) | Vrací 3D formát grafu. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze pro čtení long.

**Vrací:**
long
### getFill() {#getFill--}
```
public final IFillFormat getFill()
```

Vrací vlastnosti stylu výplně grafu. Pouze pro čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getLine() {#getLine--}
```
public final ILineFormat getLine()
```

Vrací vlastnosti stylu čáry grafu. Pouze pro čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffect() {#getEffect--}
```
public final IEffectFormat getEffect()
```

Vrací efekty použité pro graf. Pouze pro čtení [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Vrací:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getEffect3D() {#getEffect3D--}
```
public final IThreeDFormat getEffect3D()
```

Vrací 3D formát grafu. Pouze pro čtení [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Vrací:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)