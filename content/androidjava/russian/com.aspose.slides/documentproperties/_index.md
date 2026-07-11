---
title: DocumentProperties
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет свойства презентации.
type: docs
url: /ru/com.aspose.slides/documentproperties/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

Представляет свойства презентации.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // Создать экземпляр класса Presentation, представляющего презентацию
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Создать ссылку на объект IDocumentProperties, связанный с Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Отобразить встроенные свойства
>      System.out.println("Category : " + documentProperties.getCategory());
>      System.out.println("Current Status : " + documentProperties.getContentStatus());
>      System.out.println("Creation Date : " + documentProperties.getCreatedTime());
>      System.out.println("Author : " + documentProperties.getAuthor());
>      System.out.println("Description : " + documentProperties.getComments());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to modify built-in Properties of PowerPoint Presentation.
>  
>  // Создать экземпляр класса Presentation, представляющего презентацию
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Создать ссылку на объект IDocumentProperties, связанный с Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Установить встроенные свойства
>      documentProperties.setAuthor("Aspose.Slides for Android via Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // Сохранить презентацию в файл
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | Инициализирует новый экземпляр класса [DocumentProperties](../../com.aspose.slides/documentproperties). |
## Методы

| Метод | Описание |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Возвращает версию приложения. |
| [getNameOfApplication()](#getNameOfApplication--) | Возвращает или задаёт имя приложения. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Возвращает или задаёт имя приложения. |
| [getCompany()](#getCompany--) | Возвращает или задаёт свойство компании. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Возвращает или задаёт свойство компании. |
| [getManager()](#getManager--) | Возвращает или задаёт свойство менеджера. |
| [setManager(String value)](#setManager-java.lang.String-) | Возвращает или задаёт свойство менеджера. |
| [getPresentationFormat()](#getPresentationFormat--) | Возвращает или задаёт предполагаемый формат презентации. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Возвращает или задаёт предполагаемый формат презентации. |
| [getSharedDoc()](#getSharedDoc--) | Определяет, совместно используется ли презентация несколькими людьми. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Определяет, совместно используется ли презентация несколькими людьми. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Возвращает или задаёт шаблон приложения. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Возвращает или задаёт шаблон приложения. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Общее время редактирования презентации. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Общее время редактирования презентации. |
| [getTitle()](#getTitle--) | Возвращает или задаёт название презентации. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Возвращает или задаёт название презентации. |
| [getSubject()](#getSubject--) | Возвращает или задаёт тему презентации. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Возвращает или задаёт тему презентации. |
| [getAuthor()](#getAuthor--) | Возвращает или задаёт автора презентации. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Возвращает или задаёт автора презентации. |
| [getKeywords()](#getKeywords--) | Возвращает или задаёт ключевые слова презентации. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Возвращает или задаёт ключевые слова презентации. |
| [getComments()](#getComments--) | Возвращает или задаёт комментарии к презентации. |
| [setComments(String value)](#setComments-java.lang.String-) | Возвращает или задаёт комментарии к презентации. |
| [getCategory()](#getCategory--) | Возвращает или задаёт категорию презентации. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Возвращает или задаёт категорию презентации. |
| [getCreatedTime()](#getCreatedTime--) | Возвращает дату создания презентации. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Возвращает дату создания презентации. |
| [getLastSavedTime()](#getLastSavedTime--) | Возвращает дату последнего изменения презентации. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Возвращает дату последнего изменения презентации. |
| [getLastPrinted()](#getLastPrinted--) | Возвращает дату последней печати презентации. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Возвращает дату последней печати презентации. |
| [getLastSavedBy()](#getLastSavedBy--) | Возвращает или задаёт имя последнего лица, изменившего презентацию. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Возвращает или задаёт имя последнего лица, изменившего презентацию. |
| [getRevisionNumber()](#getRevisionNumber--) | Возвращает или задаёт номер версии презентации. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Возвращает или задаёт номер версии презентации. |
| [getContentStatus()](#getContentStatus--) | Возвращает или задаёт статус содержимого презентации. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Возвращает или задаёт статус содержимого презентации. |
| [getContentType()](#getContentType--) | Возвращает или задаёт тип содержимого презентации. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Возвращает или задаёт тип содержимого презентации. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Возвращает или задаёт свойство документа HyperlinkBase. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Возвращает или задаёт свойство документа HyperlinkBase. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Возвращает количество пользовательских свойств, фактически содержащихся в коллекции. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Возвращает имя пользовательского свойства по указанному индексу. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Удаляет пользовательское свойство, связанное с указанным именем. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Проверяет наличие пользовательского свойства с указанным именем. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Возвращает или задаёт пользовательское свойство, связанное с указанным именем. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Возвращает или задаёт пользовательское свойство, связанное с указанным именем. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Получает именованное логическое значение из пользовательских свойств. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Получает именованное целочисленное значение из пользовательских свойств. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Получает именованное значение DateTime из пользовательских свойств. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Получает именованное строковое значение из пользовательских свойств. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Получает именованное значение float из пользовательских свойств. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Получает именованное значение double из пользовательских свойств. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Задаёт именованное логическое пользовательское свойство. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Задаёт именованное целочисленное пользовательское свойство. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Задаёт именованное свойство DateTime. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Задаёт именованное строковое пользовательское свойство. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Задаёт именованное свойство float. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Задаёт именованное свойство double. |
| [clearCustomProperties()](#clearCustomProperties--) | Удаляет все пользовательские свойства. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Получает массив меток чувствительности из пользовательских свойств документа (Microsoft Information Protection SDK Metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Очищает и задаёт значения по умолчанию для всех встроенных свойств. |
| [getScaleCrop()](#getScaleCrop--) | Указывает режим отображения миниатюры документа. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Указывает режим отображения миниатюры документа. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Указывает, актуальны ли гиперссылки в документе. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Указывает, актуальны ли гиперссылки в документе. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Указывает, что одна или несколько гиперссылок в этой части были обновлены исключительно в этой части производителем. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Указывает, что одна или несколько гиперссылок в этой части были обновлены исключительно в этой части производителем. |
| [getSlides()](#getSlides--) | Возвращает общее количество слайдов в документе презентации. |
| [getHiddenSlides()](#getHiddenSlides--) | Возвращает количество скрытых слайдов в документе презентации. |
| [getNotes()](#getNotes--) | Возвращает количество слайдов в презентации, содержащих заметки. |
| [getParagraphs()](#getParagraphs--) | Возвращает общее количество абзацев, найденных в документе, если применимо. |
| [getWords()](#getWords--) | Возвращает общее количество слов, содержащихся в документе. |
| [getMultimediaClips()](#getMultimediaClips--) | Возвращает общее количество звуковых или видеоклипов, присутствующих в документе. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Указывает заголовок каждой части документа. Эти части не являются реальными частями документа, а являются концептуальными представлениями разделов документа. |
| [getHeadingPairs()](#getHeadingPairs--) | Указывает группировку частей документа и количество частей в каждой группе. |
| [deepClone()](#deepClone--) | Клонирует текущий объект |
| [cloneT()](#cloneT--) | Клонирует текущий объект |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

Инициализирует новый экземпляр класса [DocumentProperties](../../com.aspose.slides/documentproperties).

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

Возвращает версию приложения. Только для чтения String.

**Возвращает:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

Возвращает или задаёт имя приложения. Чтение/запись String.

**Возвращает:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

Возвращает или задаёт имя приложения. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```

Возвращает или задаёт свойство компании. Чтение/запись String.

**Возвращает:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

Возвращает или задаёт свойство компании. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```

Возвращает или задаёт свойство менеджера. Чтение/запись String.

**Возвращает:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

Возвращает или задаёт свойство менеджера. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

Возвращает или задаёт предполагаемый формат презентации. Чтение/запись String.

**Возвращает:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

Возвращает или задаёт предполагаемый формат презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

Определяет, совместно используется ли презентация несколькими людьми. Чтение/запись boolean.

**Возвращает:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

Определяет, совместно используется ли презентация несколькими людьми. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

Возвращает или задаёт шаблон приложения. Чтение/запись String.

**Возвращает:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

Возвращает или задаёт шаблон приложения. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

Общее время редактирования презентации. Чтение/запись double.

**Возвращает:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

Общее время редактирования презентации. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

Возвращает или задаёт название презентации. Чтение/запись String.

**Возвращает:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

Возвращает или задаёт название презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```

Возвращает или задаёт тему презентации. Чтение/запись String.

**Возвращает:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

Возвращает или задаёт тему презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

Возвращает или задаёт автора презентации. Чтение/запись String.

**Возвращает:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

Возвращает или задаёт автора презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

Возвращает или задаёт ключевые слова презентации. Чтение/запись String.

**Возвращает:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

Возвращает или задаёт ключевые слова презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```

Возвращает или задаёт комментарии к презентации. Чтение/запись String.

**Возвращает:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Возвращает или задаёт комментарии к презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```

Возвращает или задаёт категорию презентации. Чтение/запись String.

**Возвращает:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

Возвращает или задаёт категорию презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Возвращает дату создания презентации. Значения в UTC. Чтение/запись java.util.Date.

**Возвращает:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Возвращает дату создания презентации. Значения в UTC. Чтение/запись java.util.Date.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

Возвращает дату последнего изменения презентации. Значения в UTC. Только для чтения в случае Presentation.DocumentProperties (поскольку она обновляется внутренне во время процесса сохранения объекта IPresentation). Может быть изменено через экземпляр DocumentProperties, возвращаемый методом [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). См. пример в методе [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Возвращает:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

Возвращает дату последнего изменения презентации. Значения в UTC. Только для чтения в случае Presentation.DocumentProperties (поскольку она обновляется внутренне во время процесса сохранения объекта IPresentation). Может быть изменено через экземпляр DocumentProperties, возвращаемый методом [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). См. пример в методе [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

Возвращает дату последней печати презентации. Чтение/запись java.util.Date.

**Возвращает:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

Возвращает дату последней печати презентации. Чтение/запись java.util.Date.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

Возвращает или задаёт имя последнего лица, изменившего презентацию. Чтение/запись String.

**Возвращает:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

Возвращает или задаёт имя последнего лица, изменившего презентацию. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

Возвращает или задаёт номер версии презентации. Чтение/запись int.

**Возвращает:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

Возвращает или задаёт номер версии презентации. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```

Возвращает или задаёт статус содержимого презентации. Чтение/запись String.

**Возвращает:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

Возвращает или задаёт статус содержимого презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

Возвращает или задаёт тип содержимого презентации. Чтение/запись String.

**Возвращает:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Возвращает или задаёт тип содержимого презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

Возвращает или задаёт свойство документа HyperlinkBase. Чтение/запись String.

**Возвращает:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

Возвращает или задаёт свойство документа HyperlinkBase. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

Возвращает количество пользовательских свойств, фактически содержащихся в коллекции. Только для чтения int.

**Возвращает:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

Возвращает имя пользовательского свойства по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс свойства для получения. |

**Возвращает:**
java.lang.String - Имя пользовательского свойства по указанному индексу.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

Удаляет пользовательское свойство, связанное с указанным именем.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства для удаления. |

**Возвращает:**
boolean - true, если свойство удалено, иначе false.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

Проверяет наличие пользовательского свойства с указанным именем.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства для проверки. |

**Возвращает:**
boolean - true, если свойство существует, иначе false.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

Возвращает или задаёт пользовательское свойство, связанное с указанным именем. Чтение/запись Object.

--------------------

Значение может быть **int**, **float**, **String**, **boolean** или **Date**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String |  |

**Возвращает:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```

Возвращает или задаёт пользовательское свойство, связанное с указанным именем. Чтение/запись Object.

--------------------

Значение может быть **int**, **float**, **String**, **boolean** или **Date**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

Получает именованное логическое значение из пользовательских свойств.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства |
| value | boolean[] | Значение свойства |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

Получает именованное целочисленное значение из пользовательских свойств.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства |
| value | int[] | Значение свойства |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

Получает именованное значение DateTime из пользовательских свойств.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства |
| value | java.util.Date[] | Значение свойства |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

Получает именованное строковое значение из пользовательских свойств.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства |
| value | java.lang.String[] | Значение свойства |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

Получает именованное значение float из пользовательских свойств.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства |
| value | float[] | Значение свойства |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

Получает именованное значение double из пользовательских свойств.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства |
| value | double[] | Значение свойства |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

Задаёт именованное логическое пользовательское свойство.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства |
| value | boolean | Значение свойства |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

Задаёт именованное целочисленное пользовательское свойство.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства |
| value | int | Значение свойства |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

Задаёт именованное свойство DateTime.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства |
| value | java.util.Date | Значение свойства |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

Задаёт именованное строковое пользовательское свойство.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства |
| value | java.lang.String | Значение свойства |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

Задаёт именованное свойство float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства |
| value | float | Значение свойства |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

Задаёт именованное свойство double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства |
| value | double | Значение свойства |

### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```

Удаляет все пользовательские свойства.

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

Получает массив меток чувствительности из пользовательских свойств документа (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Получить метки чувствительности из пользовательских свойств документа
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Добавить метку в коллекцию
>          // Здесь можно добавить проверку валидности информации о метке (метка доступна и т.д.)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInBy

```

Очищает и задаёт значения по умолчанию для всех встроенных свойств.

### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

Указывает режим отображения миниатюры документа. Установите значение **true**, чтобы включить масштабирование миниатюры к дисплею. Установите значение **false**, чтобы включить обрезку миниатюры, отображая только те части, которые помещаются в дисплей. Чтение/запись boolean.

**Возвращает:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

Указывает режим отображения миниатюры документа. Установите значение **true**, чтобы включить масштабирование миниатюры к дисплею. Установите значение **false**, чтобы включить обрезку миниатюры, отображая только те части, которые помещаются в дисплей. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

Указывает, актуальны ли гиперссылки в документе. Установите значение **true**, чтобы указать, что гиперссылки обновлены. Установите значение **false**, чтобы указать, что гиперссылки устарели. Чтение/запись boolean.

**Возвращает:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```

Указывает, актуальны ли гиперссылки в документе. Установите значение **true**, чтобы указать, что гиперссылки обновлены. Установите значение **false**, чтобы указать, что гиперссылки устарели. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Указывает, что одна или несколько гиперссылок в этой части были обновлены исключительно в этой части производителем. Чтение/запись boolean.

**Возвращает:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Указывает, что одна или несколько гиперссылок в этой части были обновлены исключительно в этой части производителем. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

Возвращает общее количество слайдов в документе презентации. Только для чтения int.

**Возвращает:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Возвращает количество скрытых слайдов в документе презентации. Только для чтения int.

**Возвращает:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

Возвращает количество слайдов в презентации, содержащих заметки. Только для чтения int.

**Возвращает:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

Возвращает общее количество абзацев, найденных в документе, если применимо. Только для чтения int.

**Возвращает:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

Возвращает общее количество слов, содержащихся в документе. Только для чтения int.

**Возвращает:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Возвращает общее количество звуковых или видеоклипов, присутствующих в документе. Только для чтения int.

**Возвращает:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Указывает заголовок каждой части документа. Эти части не являются реальными частями документа, а являются концептуальными представлениями разделов документа. Только для чтения String[].

**Возвращает:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

Указывает группировку частей документа и количество частей в каждой группе. Только для чтения IHeadingPair[].

**Возвращает:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Клонирует текущий объект

**Возвращает:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Клонирует текущий объект

**Возвращает:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone