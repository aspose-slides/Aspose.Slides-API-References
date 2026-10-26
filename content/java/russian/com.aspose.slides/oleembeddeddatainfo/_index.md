---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides для Java справочник API
description: Представляет информацию о внедрённых данных для OLE-объекта.
type: docs
url: /ru/com.aspose.slides/oleembeddeddatainfo/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

Представляет информацию о внедрённых данных для OLE-объекта.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | Создаёт новую информацию о внедрённых данных для OLE-объекта. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | Создаёт новый экземпляр информации о внедрённых данных для OLE-объекта. |
## Методы

| Метод | Описание |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | Возвращает данные файла внедрённого OLE-объекта, только для чтения byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | Возвращает расширение файла текущего внедрённого OLE-объекта, только для чтения String. |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

Создаёт новую информацию о внедрённых данных для OLE-объекта.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

Создаёт новый экземпляр информации о внедрённых данных для OLE-объекта.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| embeddedFileData | byte[] | Данные файла внедрённого OLE-объекта byte[]. |
| embeddedFileExtension | java.lang.String | Расширение файла текущего внедрённого OLE-объекта String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

Возвращает данные файла внедрённого OLE-объекта, только для чтения byte[].

**Возвращаемое значение:**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

Возвращает расширение файла текущего внедрённого OLE-объекта, только для чтения String.

**Возвращаемое значение:**
java.lang.String