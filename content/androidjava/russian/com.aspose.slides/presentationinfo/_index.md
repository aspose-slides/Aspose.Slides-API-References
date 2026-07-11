---
title: PresentationInfo
second_title: Aspose.Slides для Android через справочник Java API
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

Information about presentation file
## Методы

| Метод | Описание |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Возвращает True, если связанная презентация зашифрована, иначе False. |
| [isPasswordProtected()](#isPasswordProtected--) | Возвращает значение, указывающее, защищена ли связанная презентация паролем для открытия. |
| [isWriteProtected()](#isWriteProtected--) | Возвращает значение, указывающее, защищена ли связанная презентация от записи. |
| [getLoadFormat()](#getLoadFormat--) | Возвращает формат связанной презентации. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Проверяет, является ли пароль корректным для презентации, защищённой паролем для открытия. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Проверяет, является ли пароль для изменения корректным для презентации, защищённой от записи. |
| [readDocumentProperties()](#readDocumentProperties--) | Возвращает свойства документа связанной презентации. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Обновляет свойства связанной презентации. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Записывает связанную презентацию в поток. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Записывает связанную презентацию в файл. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Возвращает True, если связанная презентация зашифрована, иначе False. Только для чтения, boolean.

**Возвращает:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Возвращает значение, указывающее, защищена ли связанная презентация паролем для открытия.

---

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

**Возвращает:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

Возвращает значение, указывающее, защищена ли связанная презентация от записи.

---

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

---

Если презентация защищена паролем для открытия, значение свойства равно NotDefined.

**Возвращает:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Возвращает формат связанной презентации. Только для чтения [LoadFormat](../../com.aspose.slides/loadformat).

**Возвращает:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

Проверяет, является ли пароль корректным для презентации, защищённой паролем для открытия.

---

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| password | java.lang.String | Пароль для проверки. |

Когда пароль равен null или пустой, этот метод возвращает false. |

**Возвращает:**
boolean - True, если презентация защищена паролем для открытия и пароль корректен, иначе false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Проверяет, является ли пароль для изменения корректным для презентации, защищённой от записи.

---

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

1. Перед вызовом этого метода следует проверить свойство (\#isWriteProtected.isWriteProtected). 2. Когда пароль равен null или пустой, этот метод возвращает false. |

**Возвращает:**
boolean - True, если презентация защищена от записи и пароль корректен. False в противном случае.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

Возвращает свойства документа связанной презентации.

**Возвращает:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

Обновляет свойства связанной презентации.

---

> ```
> Этот пример показывает, как вызвать #updateDocumentProperties(IDDocumentProperties).updateDocumentProperties(IDDocumentProperties) метод для
>  обновления свойств документа, полученных вызовом метода #readDocumentProperties.readDocumentProperties.
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

Записывает связанную презентацию в поток.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток должен поддерживать позиционирование и быть доступным для записи. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

Записывает связанную презентацию в файл.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| file | java.lang.String | Файл презентации. |