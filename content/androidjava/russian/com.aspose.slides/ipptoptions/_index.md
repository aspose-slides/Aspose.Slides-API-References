---
title: IPptOptions
second_title: Aspose.Slides для Android через справочник Java API
description: Предоставляет параметры, которые управляют тем, как презентация сохраняется в формате PPT.
type: docs
url: /ru/com.aspose.slides/ipptoptions/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

Предоставляет параметры, которые управляют тем, как презентация сохраняется в формате PPT.
## Методы

| Метод | Описание |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Представляет GUID класса объекта (CLSID), который хранится в записи корневого каталога. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Представляет GUID класса объекта (CLSID), который хранится в записи корневого каталога. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```


Представляет GUID класса объекта (CLSID), который хранится в записи корневого каталога. Может использоваться для COM-активации приложения документа. Значение по умолчанию — `'64818D11-4F9B-11CF-86EA-00AA00B929E8'`, которое соответствует `'Microsoft Powerpoint.Slide.8'`.

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
public abstract void setRootDirectoryClsid(UUID value)
```


Представляет GUID класса объекта (CLSID), который хранится в записи корневого каталога. Может использоваться для COM-активации приложения документа. Значение по умолчанию — `'64818D11-4F9B-11CF-86EA-00AA00B929E8'`, которое соответствует `'Microsoft Powerpoint.Slide.8'`.

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