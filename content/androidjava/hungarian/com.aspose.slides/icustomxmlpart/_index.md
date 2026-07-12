---
title: ICustomXmlPart
second_title: Aspose.Slides for Android via Java API Reference
description: A testreszabott XML részt képviseli.
type: docs
url: /hu/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

A testreszabott XML részt képviseli.
## Módszerek

| Method | Description |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Visszaadja vagy beállítja az xml adatot UTF-8 karakterláncként. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Visszaadja vagy beállítja az xml adatot UTF-8 karakterláncként. |
| [getXmlData()](#getXmlData--) | Visszaadja vagy beállítja az xml adatot. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Returns or sets xml data. |
| [getItemId()](#getItemId--) | Megad egy globálisan egyedi azonosítót (GUID), amely egyedileg azonosít egyetlen testreszabott XML részt egy Office Open XML dokumentumban. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Megad egy globálisan egyedi azonosítót (GUID), amely egyedileg azonosít egyetlen testreszabott XML részt egy Office Open XML dokumentumban. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Visszaadja az XML sémák gyűjteményét, amely a testreszabott XML részhez kapcsolódik. |
| [remove()](#remove--) | Eltávolítja a testreszabott xml részt a bemutatóból. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```


Visszaadja vagy beállítja az xml adatot UTF-8 karakterláncként. Olvasás/írás String.

**Visszatér:**  
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```


Visszaadja vagy beállítja az xml adatot UTF-8 karakterláncként. Olvasás/írás String.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```


Visszaadja vagy beállítja az xml adatot. Olvasás/írás byte[].

**Visszatér:**  
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```


Visszaadja vagy beállítja az xml adatot. Olvasás/írás byte[].

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```


Megad egy globálisan egyedi azonosítót (GUID), amely egyedileg azonosít egyetlen testreszabott XML részt egy Office Open XML dokumentumban. Csak olvasható java.util.UUID.

**Visszatér:**  
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```


Megad egy globálisan egyedi azonosítót (GUID), amely egyedileg azonosít egyetlen testreszabott XML részt egy Office Open XML dokumentumban. Csak olvasható java.util.UUID.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```


Visszaadja az XML sémák gyűjteményét, amely a testreszabott XML részhez kapcsolódik. Csak olvasható String[].

**Visszatér:**  
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```


Eltávolítja a testreszabott xml részt a bemutatóból.