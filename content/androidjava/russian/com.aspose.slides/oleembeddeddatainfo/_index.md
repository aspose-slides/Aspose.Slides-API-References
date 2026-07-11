---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет информацию о встроенных данных для OLE-объекта.
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

Представляет информацию о внедренных данных для OLE-объекта.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | Создает новую информацию о внедренных данных для OLE-объекта. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | Создает новый экземпляр информации о внедренных данных для OLE-объекта. |
## Методы

| Метод | Описание |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | Возвращает данные файла встроенного OLE-объекта, только для чтения byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | Возвращает расширение файла текущего встроенного OLE-объекта, только для чтения String. |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

Создает новую информацию о внедренных данных для OLE-объекта.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

Создает новый экземпляр информации о внедренных данных для OLE-объекта.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| embeddedFileData | byte[] | Данные файла встроенного OLE-объекта byte[]. |
| embeddedFileExtension | java.lang.String | Расширение файла текущего встроенного OLE-объекта String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

Возвращает данные файла встроенного OLE-объекта, только для чтения byte[].

**Возвращаемое значение:**  
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

Возвращает расширение файла текущего встроенного OLE-объекта, только для чтения String.

**Возвращаемое значение:**  
java.lang.String