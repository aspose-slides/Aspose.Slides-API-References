---
title: IPresentationInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Information about presentation file
type: docs
url: /ru/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

Сведения о файле презентации
## Методы

| Method | Description |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Возвращает True, если привязанная презентация зашифрована, иначе False. |
| [isPasswordProtected()](#isPasswordProtected--) | Возвращает значение, указывающее, защищена ли привязанная презентация паролем для открытия. |
| [isWriteProtected()](#isWriteProtected--) | Возвращает значение, указывающее, защищена ли привязанная презентация от записи. |
| [getLoadFormat()](#getLoadFormat--) | Возвращает формат привязанной презентации. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Проверяет, правильный ли пароль для презентации, защищенной паролем для открытия. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Проверяет, правильный ли пароль для изменения презентации, защищённой от записи. |
| [readDocumentProperties()](#readDocumentProperties--) | Возвращает свойства документа привязанной презентации. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Обновляет свойства привязанной презентации. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Записывает привязанную презентацию в поток. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Записывает привязанную презентацию в файл. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Возвращает True, если привязанная презентация зашифрована, иначе False. Только для чтения boolean.

**Возвращаемое значение:**  
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Возвращает значение, указывающее, защищена ли привязанная презентация паролем для открытия.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```

**Возвращаемое значение:**  
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

Возвращает значение, указывающее, защищена ли привязанная презентация от записи.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```

--------------------

Если презентация защищена паролем для открытия, значение свойства равно NotDefined. См. перечисление [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**  
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Возвращает формат привязанной презентации. Только для чтения [LoadFormat](../../com.aspose.slides/loadformat).

**Возвращаемое значение:**  
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

Проверяет, правильный ли пароль для презентации, защищенной паролем для открытия.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| password | java.lang.String | Проверяемый пароль. |

--------------------

Когда пароль равен null или пустой, этот метод возвращает false. |

**Возвращаемое значение:**  
boolean - True, если презентация защищена паролем для открытия и пароль правильный, иначе false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Проверяет, правильный ли пароль для изменения презентации, защищённой от записи.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| password | java.lang.String | Проверяемый пароль. |

--------------------

1. Вы должны проверить свойство (\#isWriteProtected.isWriteProtected) перед вызовом этого метода. 2. Когда пароль равен null или пустой, этот метод возвращает false. |

**Возвращаемое значение:**  
boolean - True, если презентация защищена от записи и пароль правильный. False в противном случае.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

Возвращает свойства документа привязанной презентации.

**Возвращаемое значение:**  
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Свойства документа [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

Обновляет свойства привязанной презентации.

--------------------

> ```
> This sample shows how to call the #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) method to
>  update the document properties returned by call of the #readDocumentProperties.readDocumentProperties method.
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
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | Свойства документа [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

Записывает привязанную презентацию в поток.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток должен поддерживать поиск и быть записываемым. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

Записывает привязанную презентацию в файл.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| file | java.lang.String | Файл презентации. |