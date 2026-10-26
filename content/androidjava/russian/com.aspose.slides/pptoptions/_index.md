---
title: PptOptions
second_title: Aspose.Slides для Android через справочник Java API
description: Предоставляет параметры, которые контролируют, как презентация сохраняется в формате PPT.
type: docs
url: /ru/com.aspose.slides/pptoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Все реализованные интерфейсы:**
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

Предоставляет параметры, которые контролируют, как презентация сохраняется в формате PPT.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Представляет GUID (CLSID) класса объекта, хранящийся в корневой записи каталога. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Представляет GUID (CLSID) класса объекта, хранящийся в корневой записи каталога. |
### PptOptions() {#PptOptions--}
```
public PptOptions()
```


### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```


Представляет GUID (CLSID) класса объекта, хранящийся в корневой записи каталога. Можно использовать для COM-активации приложения документа. Значение по умолчанию — '64818D11-4F9B-11CF-86EA-00AA00B929E8' которое соответствует 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// установить CLSID в 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public final void setRootDirectoryClsid(UUID value)
```


Представляет GUID (CLSID) класса объекта, хранящийся в корневой записи каталога. Можно использовать для COM-активации приложения документа. Значение по умолчанию — '64818D11-4F9B-11CF-86EA-00AA00B929E8' которое соответствует 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// установить CLSID в 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.UUID |  |