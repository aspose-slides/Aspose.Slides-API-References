---
title: DocumentProperties
second_title: Справочник API Aspose.Slides для Java
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
>      // Создать ссылку на объект IDocumentProperties, связанный с презентацией
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
>      // Создать ссылку на объект IDocumentProperties, связанный с презентацией
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Установить встроенные свойства
>      documentProperties.setAuthor("Aspose.Slides for Java");
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
| [getNameOfApplication()](#getNameOfApplication--) | Возвращает или задает название приложения. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Возвращает или задает название приложения. |
| [getCompany()](#getCompany--) | Возвращает или задает свойство компании. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Возвращает или задает свойство компании. |
| [getManager()](#getManager--) | Возвращает или задает свойство менеджера. |
| [setManager(String value)](#setManager-java.lang.String-) | Возвращает или задает свойство менеджера. |
| [getPresentationFormat()](#getPresentationFormat--) | Возвращает или задает предполагаемый формат презентации. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Возвращает или задает предполагаемый формат презентации. |
| [getSharedDoc()](#getSharedDoc--) | Определяет, является ли презентация совместно используемой несколькими людьми. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Определяет, является ли презентация совместно используемой несколькими людьми. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Возвращает или задает шаблон приложения. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Возвращает или задает шаблон приложения. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Общее время редактирования презентации. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Общее время редактирования презентации. |
| [getTitle()](#getTitle--) | Возвращает или задает заголовок презентации. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Возвращает или задает заголовок презентации. |
| [getSubject()](#getSubject--) | Возвращает или задает тему презентации. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Возвращает или задает тему презентации. |
| [getAuthor()](#getAuthor--) | Возвращает или задает автора презентации. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Возвращает или задает автора презентации. |
| [getKeywords()](#getKeywords--) | Возвращает или задает ключевые слова презентации. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Возвращает или задает ключевые слова презентации. |
| [getComments()](#getComments--) | Возвращает или задает комментарии презентации. |
| [setComments(String value)](#setComments-java.lang.String-) | Возвращает или задает комментарии презентации. |
| [getCategory()](#getCategory--) | Возвращает или задает категорию презентации. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Возвращает или задает категорию презентации. |
| [getCreatedTime()](#getCreatedTime--) | Возвращает дату создания презентации. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Возвращает дату создания презентации. |
| [getLastSavedTime()](#getLastSavedTime--) | Возвращает дату последнего изменения презентации. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Возвращает дату последнего изменения презентации. |
| [getLastPrinted()](#getLastPrinted--) | Возвращает дату последней печати презентации. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Возвращает дату последней печати презентации. |
| [getLastSavedBy()](#getLastSavedBy--) | Возвращает или задает имя последнего пользователя, изменившего презентацию. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Возвращает или задает имя последнего пользователя, изменившего презентацию. |
| [getRevisionNumber()](#getRevisionNumber--) | Возвращает или задает номер ревизии презентации. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Возвращает или задает номер ревизии презентации. |
| [getContentStatus()](#getContentStatus--) | Возвращает или задает статус содержимого презентации. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Возвращает или задает статус содержимого презентации. |
| [getContentType()](#getContentType--) | Возвращает или задает тип содержимого презентации. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Возвращает или задает тип содержимого презентации. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Возвращает или задает свойство документа HyperlinkBase. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Возвращает или задает свойство документа HyperlinkBase. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Возвращает количество пользовательских свойств, реально содержащихся в коллекции. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Возвращает имя пользовательского свойства по указанному индексу. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Удаляет пользовательское свойство, связанное с указанным именем. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Проверяет наличие пользовательского свойства с указанным именем. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Возвращает или задает пользовательское свойство, связанное с указанным именем. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Возвращает или задает пользовательское свойство, связанное с указанным именем. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Получает именованное логическое значение из пользовательских свойств. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Получает именованное целочисленное значение из пользовательских свойств. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Получает именованное значение DateTime из пользовательских свойств. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Получает именованное строковое значение из пользовательских свойств. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Получает именованное значение float из пользовательских свойств. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Получает именованное значение double из пользовательских свойств. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Устанавливает именованное логическое пользовательское свойство. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Устанавливает именованное целочисленное пользовательское свойство. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Устанавливает именованное свойство DateTime. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Устанавливает именованное строковое пользовательское свойство. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Устанавливает именованное пользовательское свойство типа float. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Устанавливает именованное пользовательское свойство типа double. |
| [clearCustomProperties()](#clearCustomProperties--) | Удаляет все пользовательские свойства. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Получает массив меток чувствительности из пользовательских свойств документа (Microsoft Information Protection SDK Metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Очищает и задает значения по умолчанию для всех встроенных свойств. |
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
| [getTitlesOfParts()](#getTitlesOfParts--) | Указывает заголовок каждой части документа. |
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


Возвращает или задает название приложения. Чтение/запись String.

**Возвращает:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```


Возвращает или задает название приложения. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```


Возвращает или задает свойство компании. Чтение/запись String.

**Возвращает:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


Возвращает или задает свойство компании. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```


Возвращает или задает свойство менеджера. Чтение/запись String.

**Возвращает:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```


Возвращает или задает свойство менеджера. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```


Возвращает или задает предполагаемый формат презентации. Чтение/запись String.

**Возвращает:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```


Возвращает или задает предполагаемый формат презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```


Определяет, является ли презентация совместно используемой несколькими людьми. Чтение/запись boolean.

**Возвращает:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```


Определяет, является ли презентация совместно используемой несколькими людьми. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```


Возвращает или задает шаблон приложения. Чтение/запись String.

**Возвращает:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```


Возвращает или задает шаблон приложения. Чтение/запись String.

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


Возвращает или задает заголовок презентации. Чтение/запись String.

**Возвращает:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Возвращает или задает заголовок презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Возвращает или задает тему презентации. Чтение/запись String.

**Возвращает:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Возвращает или задает тему презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Возвращает или задает автора презентации. Чтение/запись String.

**Возвращает:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Возвращает или задает автора презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```


Возвращает или задает ключевые слова презентации. Чтение/запись String.

**Возвращает:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```


Возвращает или задает ключевые слова презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Возвращает или задает комментарии презентации. Чтение/запись String.

**Возвращает:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Возвращает или задает комментарии презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```


Возвращает или задает категорию презентации. Чтение/запись String.

**Возвращает:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```


Возвращает или задает категорию презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```
Возвращает дату создания презентации. Значения указаны в UTC. Чтение/запись java.util.Date.

**Возвращает:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Возвращает дату создания презентации. Значения указаны в UTC. Чтение/запись java.util.Date.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

Возвращает дату последнего изменения презентации. Значения указаны в UTC. Только для чтения в случае Presentation.DocumentProperties (поскольку она будет обновляться внутренне во время процесса сохранения объекта IPresentation). Может быть изменено через экземпляр DocumentProperties, возвращаемый методом [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). См. пример в методе [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Возвращает:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

Возвращает дату последнего изменения презентации. Значения указаны в UTC. Только для чтения в случае Presentation.DocumentProperties (поскольку она будет обновляться внутренне во время процесса сохранения объекта IPresentation). Может быть изменено через экземпляр DocumentProperties, возвращаемый методом [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). См. пример в методе [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

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

Возвращает или задаёт имя последнего человека, изменившего презентацию. Чтение/запись String.

**Возвращает:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

Возвращает или задаёт имя последнего человека, изменившего презентацию. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

Возвращает или задаёт номер ревизии презентации. Чтение/запись int.

**Возвращает:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

Возвращает или задаёт номер ревизии презентации. Чтение/запись int.

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
| index | int | Нулевой индекс пользовательского свойства для получения. |

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
| name | java.lang.String | Имя пользовательского свойства для удаления. |

**Возвращает:**
boolean - Возвращает true, если свойство было удалено, иначе false.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

Проверяет наличие пользовательского свойства с указанным именем.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для проверки. |

**Возвращает:**
boolean - Возвращает true, если свойство существует, иначе false.
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
| name | java.lang.String | Имя пользовательского свойства для получения |
| value | boolean[] | Значение пользовательского свойства |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

Получает именованное целочисленное значение из пользовательских свойств.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для получения |
| value | int[] | Значение пользовательского свойства |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

Получает именованное значение DateTime из пользовательских свойств.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для получения |
| value | java.util.Date[] | Значение пользовательского свойства |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

Получает именованное строковое значение из пользовательских свойств.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для получения |
| value | java.lang.String[] | Значение пользовательского свойства |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

Получает именованное значение float из пользовательских свойств.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для получения |
| value | float[] | Значение пользовательского свойства |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

Получает именованное значение double из пользовательских свойств.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для получения. |
| value | double[] | Значение пользовательского свойства |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

Устанавливает именованное логическое пользовательское свойство.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для установки |
| value | boolean | Значение пользовательского свойства |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

Устанавливает именованное целочисленное пользовательское свойство.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для установки |
| value | int | Значение пользовательского свойства |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

Устанавливает именованное значение DateTime пользовательского свойства.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для установки |
| value | java.util.Date | Значение пользовательского свойства |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

Устанавливает именованное строковое пользовательское свойство.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для установки |
| value | java.lang.String | Значение пользовательского свойства |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

Устанавливает именованное значение float пользовательского свойства.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для установки |
| value | float | Значение пользовательского свойства |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

Устанавливает именованное значение double пользовательского свойства.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для установки |
| value | double | Значение пользовательского свойства |

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
>      // Get sensitivity labels from the custom document properties
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Add label to the collection
>          // Here you can add a check for the validity of the label information (the label is available, etc)
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
public final void clearBuiltInProperties()
```

Очищает и задаёт значения по умолчанию для всех встроенных свойств.

### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

Указывает режим отображения миниатюры документа. Установите этот элемент в **true**, чтобы включить масштабирование миниатюры документа под отображение. Установите этот элемент в **false**, чтобы включить обрезку миниатюры документа, показывая только те части, которые помещаются в отображение. Чтение/запись boolean.

**Возвращает:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

Указывает режим отображения миниатюры документа. Установите этот элемент в **true**, чтобы включить масштабирование миниатюры документа под отображение. Установите этот элемент в **false**, чтобы включить обрезку миниатюры документа, показывая только те части, которые помещаются в отображение. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

Указывает, актуальны ли гиперссылки в документе. Установите этот элемент в **true**, чтобы указать, что гиперссылки обновлены. Установите этот элемент в **false**, чтобы указать, что гиперссылки устарели. Чтение/запись boolean.

**Возвращает:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```
Указывает, актуальны ли гиперссылки в документе. Установите этот элемент в **true**, чтобы указать, что гиперссылки обновлены. Установите этот элемент в **false**, чтобы указать, что гиперссылки устарели. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Указывает, что одна или несколько гиперссылок в этой части были обновлены исключительно в этой части производителем. Следующий производитель, открывающий этот документ, должен обновить отношения гиперссылок новыми гиперссылками, указанными в этой части. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Указывает, что одна или несколько гиперссылок в этой части были обновлены исключительно в этой части производителем. Следующий производитель, открывающий этот документ, должен обновить отношения гиперссылок новыми гиперссылками, указанными в этой части. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

Возвращает общее количество слайдов в документе презентации. Только чтение int.

**Возвращаемое значение:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Возвращает количество скрытых слайдов в документе презентации. Только чтение int.

**Возвращаемое значение:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

Возвращает количество слайдов в презентации, содержащих заметки. Только чтение int.

**Возвращаемое значение:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

Возвращает общее количество абзацев, найденных в документе, если применимо. Только чтение int.

**Возвращаемое значение:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

Возвращает общее количество слов, содержащихся в документе. Только чтение int.

**Возвращаемое значение:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Возвращает общее количество звуковых или видеоклипов, присутствующих в документе. Только чтение int.

**Возвращаемое значение:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Указывает название каждой части документа. Эти части не являются частями документа, а концептуальными представлениями разделов документа. Только чтение String[].

**Возвращаемое значение:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

Указывает группировку частей документа и количество частей в каждой группе. Только чтение IHeadingPair[].

**Возвращаемое значение:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Клонирует текущий объект

**Возвращаемое значение:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Клонирует текущий объект

**Возвращаемое значение:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone