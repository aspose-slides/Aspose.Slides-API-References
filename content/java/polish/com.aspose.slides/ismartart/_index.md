---
title: ISmartArt
second_title: Aspose.Slides dla dokumentacji API języka Java
description: Reprezentuje diagram SmartArt.
type: docs
url: /pl/com.aspose.slides/ismartart/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

Represents a SmartArt diagram.
## Metody

| Metoda | Opis |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Zwraca kolekcje wszystkich węzłów w obiekcie SmartArt. |
| [getNodes()](#getNodes--) | Zwraca kolekcje węzłów głównych w obiekcie SmartArt. |
| [getLayout()](#getLayout--) | Zwraca lub ustawia układ obiektu SmartArt. |
| [setLayout(int value)](#setLayout-int-) | Zwraca lub ustawia układ obiektu SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | Zwraca lub ustawia szybki styl obiektu SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Zwraca lub ustawia szybki styl obiektu SmartArt. |
| [getColorStyle()](#getColorStyle--) | Zwraca lub ustawia styl kolorów obiektu SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | Zwraca lub ustawia styl kolorów obiektu SmartArt. |
| [isReversed()](#isReversed--) | Zwraca lub ustawia stan diagramu SmartArt w odniesieniu do (left-to-right) LTR lub (right-to-left) RTL, jeśli diagram obsługuje odwrócenie. |
| [setReversed(boolean value)](#setReversed-boolean-) | Zwraca lub ustawia stan diagramu SmartArt w odniesieniu do (left-to-right) LTR lub (right-to-left) RTL, jeśli diagram obsługuje odwrócenie. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```


Zwraca kolekcje wszystkich węzłów w obiekcie SmartArt. Tylko do odczytu [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Zwraca:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```


Zwraca kolekcje węzłów głównych w obiekcie SmartArt. Tylko do odczytu [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Zwraca:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Zwraca lub ustawia układ obiektu SmartArt. Odczyt/zapis [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Zwraca:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```


Zwraca lub ustawia układ obiektu SmartArt. Odczyt/zapis [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```


Zwraca lub ustawia szybki styl obiektu SmartArt. Odczyt/zapis [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Zwraca:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```


Zwraca lub ustawia szybki styl obiektu SmartArt. Odczyt/zapis [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```


Zwraca lub ustawia styl kolorów obiektu SmartArt. Odczyt/zapis [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Zwraca:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```


Zwraca lub ustawia styl kolorów obiektu SmartArt. Odczyt/zapis [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```


Zwraca lub ustawia stan diagramu SmartArt w odniesieniu do (left-to-right) LTR lub (right-to-left) RTL, jeśli diagram obsługuje odwrócenie. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```


Zwraca lub ustawia stan diagramu SmartArt w odniesieniu do (left-to-right) LTR lub (right-to-left) RTL, jeśli diagram obsługuje odwrócenie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |