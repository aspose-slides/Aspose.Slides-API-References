---
title: PresentationInfo
second_title: Справочник API Aspose.Slides для Java
description: Информация о файле презентации
type: docs
url: /ru/com.aspose.slides/presentationinfo/
---
**Наследование:**  
java.lang.Object

**Все реализованные интерфейсы:**  
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)  
```
public final class PresentationInfo implements IPresentationInfo
```

Информация о файле презентации
## Методы

| Метод | Описание |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Возвращает True, если привязанная презентация зашифрована, иначе False. |
| [isPasswordProtected()](#isPasswordProtected--) | Возвращает значение, указывающее, защищена ли привязанная презентация паролем для открытия. |
| [isWriteProtected()](#isWriteProtected--) | Возвращает значение, указывающее, защищена ли привязанная презентация от записи. |
| [getLoadFormat()](#getLoadFormat--) | Возвращает формат привязанной презентации. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Проверяет, является ли пароль правильным для презентации, защищённой паролем открытия. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Проверяет, является ли пароль для изменения правильным для презентации, защищённой от записи. |
| [readDocumentProperties()](#readDocumentProperties--) | Возвращает свойства документа привязанной презентации. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Обновляет свойства привязанной презентации. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Записывает привязанную презентацию в поток. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Записывает привязанную презентацию в файл. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Возвращает True, если привязанная презентация зашифрована, иначе False. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Возвращает значение, указывающее, защищена ли привязанная презентация паролем для открытия.

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

**Возвращаемое значение:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

Возвращает значение, указывающее, защищена ли привязанная презентация от записи.

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

Если презентация защищена паролем для открытия, значение свойства равно NotDefined.

**Возвращаемое значение:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Возвращает формат привязанной презентации. Только для чтения [LoadFormat](../../com.aspose.slides/loadformat).

**Возвращаемое значение:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

Проверяет, является ли пароль правильным для презентации, защищённой паролем открытия.

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| password | java.lang.String | Пароль для проверки. |

Когда пароль равен null или пустой, этот метод возвращает false.

**Возвращаемое значение:**
boolean - True если презентация защищена паролем открытия и пароль правильный, иначе false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Проверяет, является ли пароль для изменения правильным для презентации, защищённой от записи.

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| password | java.lang.String | Пароль для проверки. |

1. Перед вызовом этого метода следует проверить свойство (\#isWriteProtected.isWriteProtected). 2. Когда пароль равен null или пустой, этот метод возвращает false.

**Возвращаемое значение:**
boolean - True если презентация защищена от записи и пароль правильный. False в противном случае.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

Возвращает свойства документа привязанной презентации.

**Возвращаемое значение:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

Обновляет свойства привязанной презентации.

> ```
> Этот пример показывает, как вызвать метод #updateDocumentProperties(IDDocumentProperties).updateDocumentProperties(IDDocumentProperties) 
>  обновить свойства документа, возвращенные вызовом метода #readDocumentProperties.readDocumentProperties. 
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

Записывает привязанную презентацию в поток.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток должен поддерживать перемещение и быть записываемым. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

Записывает привязанную презентацию в файл.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| file | java.lang.String | Файл презентации. |