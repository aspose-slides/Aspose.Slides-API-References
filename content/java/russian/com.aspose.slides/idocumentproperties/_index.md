---
title: IDocumentProperties
second_title: Aspose.Slides for Java API Reference
description: Представляет свойства презентации.
type: docs
url: /ru/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

Представляет свойства презентации.
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
| [getPresentationFormat()](#getPresentationFormat--) | Возвращает или задаёт предназначенный формат презентации. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Возвращает или задаёт предназначенный формат презентации. |
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
| [getLastSavedBy()](#getLastSavedBy--) | Возвращает или задаёт имя последнего пользователя, изменившего презентацию. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Возвращает или задаёт имя последнего пользователя, изменившего презентацию. |
| [getRevisionNumber()](#getRevisionNumber--) | Возвращает или задаёт номер ревизии презентации. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Возвращает или задаёт номер ревизии презентации. |
| [getContentStatus()](#getContentStatus--) | Возвращает или задаёт статус содержимого презентации. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Возвращает или задаёт статус содержимого презентации. |
| [getContentType()](#getContentType--) | Возвращает или задаёт тип содержимого презентации. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Возвращает или задаёт тип содержимого презентации. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Возвращает или задаёт свойство документа HyperlinkBase. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Возвращает или задаёт свойство документа HyperlinkBase. |
| [getScaleCrop()](#getScaleCrop--) | Указывает режим отображения эскиза документа. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Указывает режим отображения эскиза документа. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Указывает, актуальны ли гиперссылки в документе. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Указывает, актуальны ли гиперссылки в документе. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Указывает, что одна или несколько гиперссылок в этой части были обновлены исключительно в этой части производителем. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Указывает, что одна или несколько гиперссылок в этой части были обновлены исключительно в этой части производителем. |
| [getSlides()](#getSlides--) | Указывает общее количество слайдов в документе презентации. |
| [getHiddenSlides()](#getHiddenSlides--) | Указывает количество скрытых слайдов в документе презентации. |
| [getNotes()](#getNotes--) | Указывает количество слайдов в презентации, содержащих заметки. |
| [getParagraphs()](#getParagraphs--) | Указывает общее количество абзацев в документе, если применимо. |
| [getWords()](#getWords--) | Указывает общее количество слов в документе. |
| [getMultimediaClips()](#getMultimediaClips--) | Указывает общее количество звуковых или видеоклипов, присутствующих в документе. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Указывает заголовок каждой части документа. |
| [getHeadingPairs()](#getHeadingPairs--) | Указывает группировку частей документа и количество частей в каждой группе. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Возвращает количество пользовательских свойств, действительно содержащихся в коллекции. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Возвращает имя пользовательского свойства по указанному индексу. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Удаляет пользовательское свойство, связанное с указанным именем. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Проверяет наличие пользовательского свойства с указанным именем. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Возвращает или задаёт пользовательское свойство, связанное с указанным именем. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Возвращает или задаёт пользовательское свойство, связанное с указанным именем. |
| [clearCustomProperties()](#clearCustomProperties--) | Удаляет все пользовательские свойства. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Очищает и устанавливает значения по умолчанию для всех встроенных свойств. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Получает именованное логическое значение из пользовательских свойств. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Получает именованное целочисленное значение из пользовательских свойств. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Получает именованное значение DateTime из пользовательских свойств. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Получает именованное строковое значение из пользовательских свойств. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Получает именованное значение float из пользовательских свойств. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Получает именованное значение double из пользовательских свойств. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Устанавливает именованное логическое пользовательское свойство. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Устанавливает именованное целочисленное пользовательское свойство. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Устанавливает именованное значение DateTime пользовательского свойства. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Устанавливает именованное строковое пользовательское свойство. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Устанавливает именованное свойство типа float. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Устанавливает именованное свойство типа double. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Получает массив меток конфиденциальности из пользовательских свойств документа (Microsoft Information Protection SDK Metadata). |

### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

Возвращает версию приложения. Только для чтения String.

**Возвращает:**
java.lang.String

Содержимое этого элемента должно иметь форму XX.YYYY, где X и Y представляют числовые значения; в противном случае документ считается несоответствующим. Aspose.Slides представляет свою версию в формате XX.YY.ZZ, где: XX — основная версия YY — минорная версия ZZ — версия исправления. Например, значение 23.0105 означает версию Aspose.Slides 23.1.5.

### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

Возвращает или задаёт имя приложения. Чтение/запись String.

**Возвращает:**
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

Возвращает или задаёт имя приложения. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

Возвращает или задаёт свойство компании. Чтение/запись String.

**Возвращает:**
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

Возвращает или задаёт свойство компании. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```

Возвращает или задаёт свойство менеджера. Чтение/запись String.

**Возвращает:**
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

Возвращает или задаёт свойство менеджера. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

Возвращает или задаёт предназначенный формат презентации. Чтение/запись String.

**Возвращает:**
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

Возвращает или задаёт предназначенный формат презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

Определяет, совместно используется ли презентация несколькими людьми. Чтение/запись boolean.

**Возвращает:**
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

Определяет, совместно используется ли презентация несколькими людьми. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

Возвращает или задаёт шаблон приложения. Чтение/запись String.

**Возвращает:**
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

Возвращает или задаёт шаблон приложения. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

Общее время редактирования презентации. Чтение/запись double.

**Возвращает:**
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

Общее время редактирования презентации. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

Возвращает или задаёт название презентации. Чтение/запись String.

**Возвращает:**
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

Возвращает или задаёт название презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

Возвращает или задаёт тему презентации. Чтение/запись String.

**Возвращает:**
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

Возвращает или задаёт тему презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

Возвращает или задаёт автора презентации. Чтение/запись String.

**Возвращает:**
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

Возвращает или задаёт автора презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

Возвращает или задаёт ключевые слова презентации. Чтение/запись String.

**Возвращает:**
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

Возвращает или задаёт ключевые слова презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

Возвращает или задаёт комментарии к презентации. Чтение/запись String.

**Возвращает:**
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

Возвращает или задаёт комментарии к презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

Возвращает или задаёт категорию презентации. Чтение/запись String.

**Возвращает:**
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

Возвращает или задаёт категорию презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Возвращает дату создания презентации. Значения указаны в UTC. Чтение/запись java.util.Date.

**Возвращаемое значение:**
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Возвращает дату создания презентации. Значения указаны в UTC. Чтение/запись java.util.Date.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

Возвращает дату последнего изменения презентации. Значения указаны в UTC. Параметр только для чтения в случае Presentation.DocumentProperties (поскольку он будет обновлен внутренне во время процесса сохранения объекта IPresentation). Может быть изменён через экземпляр DocumentProperties, возвращаемый методом [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). См. пример в описании метода [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Возвращаемое значение:**
java.util.Date

### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

Возвращает дату последнего изменения презентации. Значения указаны в UTC. Параметр только для чтения в случае Presentation.DocumentProperties (поскольку он будет обновлен внутренне во время процесса сохранения объекта IPresentation). Может быть изменён через экземпляр DocumentProperties, возвращаемый методом [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). См. пример в описании метода [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

Возвращает дату последней печати презентации. Чтение/запись java.util.Date.

**Возвращаемое значение:**
java.util.Date

### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

Возвращает дату последней печати презентации. Чтение/запись java.util.Date.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

Возвращает или задаёт имя последнего пользователя, изменившего презентацию. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String

### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

Возвращает или задаёт имя последнего пользователя, изменившего презентацию. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

Возвращает или задаёт номер ревизии презентации. Чтение/запись int.

**Возвращаемое значение:**
int

### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

Возвращает или задаёт номер ревизии презентации. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

Возвращает или задаёт статус содержания презентации. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String

### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

Возвращает или задаёт статус содержания презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Возвращает или задаёт тип содержания презентации. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

Возвращает или задаёт тип содержания презентации. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

Возвращает или задаёт свойство документа HyperlinkBase. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

Возвращает или задаёт свойство документа HyperlinkBase. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

Указывает режим отображения миниатюры документа. Установите **true**, чтобы включить масштабирование миниатюры до размеров экрана. Установите **false**, чтобы включить обрезку миниатюры и показывать только те части, которые помещаются на экране. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

Указывает режим отображения миниатюры документа. Установите **true**, чтобы включить масштабирование миниатюры до размеров экрана. Установите **false**, чтобы включить обрезку миниатюры и показывать только те части, которые помещаются на экране. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

Указывает, актуальны ли гиперссылки в документе. Установите **true**, чтобы отметить гиперссылки как обновлённые. Установите **false**, чтобы отметить их как устаревшие. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

Указывает, актуальны ли гиперссылки в документе. Установите **true**, чтобы отметить гиперссылки как обновлённые. Установите **false**, чтобы отметить их как устаревшие. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

Указывает, что одна или несколько гиперссылок в этой части были обновлены исключительно в этой части производителем. Следующий производитель, открывающий документ, должен обновить отношения гиперссылок новыми гиперссылками, указанными в этой части. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

Указывает, что одна или несколько гиперссылок в этой части были обновлены исключительно в этой части производителем. Следующий производитель, открывающий документ, должен обновить отношения гиперссылок новыми гиперссылками, указанными в этой части. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

Определяет общее количество слайдов в документе презентации. Только для чтения int.

**Возвращаемое значение:**
int

### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

Определяет количество скрытых слайдов в документе презентации. Только для чтения int.

**Возвращаемое значение:**
int

### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

Определяет количество слайдов в презентации, содержащих заметки. Только для чтения int.

**Возвращаемое значение:**
int

### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

Определяет общее количество абзацев, найденных в документе, если применимо. Только для чтения int.

**Возвращаемое значение:**
int

### getWords() {#getWords--}
```
public abstract int getWords()
```

Определяет общее количество слов, содержащихся в документе. Только для чтения int.

**Возвращаемое значение:**
int

### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

Определяет общее количество звуковых или видеоклипов, присутствующих в документе. Только для чтения int.

**Возвращаемое значение:**
int

### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

Определяет заголовок каждой части документа. Эти части не являются реальными частями документа, а концептуальными представлениями его разделов. Только для чтения java.lang.String[].

**Возвращаемое значение:**
java.lang.String[]

### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

Указывает группировку частей документа и количество частей в каждой группе. Только для чтения com.aspose.slides.IHeadingPair[].

**Возвращаемое значение:**
com.aspose.slides.IHeadingPair[]

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

Возвращает количество пользовательских свойств, фактически содержащихся в коллекции. Только для чтения int.

**Возвращаемое значение:**
int

### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

Возвращает имя пользовательского свойства по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс пользовательского свойства для получения. |

**Возвращаемое значение:**
java.lang.String - имя пользовательского свойства по указанному индексу.

### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

Удаляет пользовательское свойство, связанное с указанным именем.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для удаления. |

**Возвращаемое значение:**
boolean - Возвращает true, если свойство было удалено, иначе false.

### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

Проверяет наличие пользовательского свойства с указанным именем.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для проверки. |

**Возвращаемое значение:**
boolean - Возвращает true, если свойство существует, иначе false.

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

Возвращает или задаёт пользовательское свойство, связанное с указанным именем. Чтение/запись Object.

--------------------

Значение может быть **int**, **float**, **double**, **String**, **boolean** или **Date**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String |  |

**Возвращаемое значение:**
java.lang.Object

### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

Возвращает или задаёт пользовательское свойство, связанное с указанным именем. Чтение/запись Object.

--------------------

Значение может быть **int**, **float**, **double**, **String**, **boolean** или **Date**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

Удаляет все пользовательские свойства.

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

Очищает и задаёт значения по умолчанию для всех встроенных свойств.

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

Получает именованное логическое значение из пользовательских свойств.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для получения |
| value | boolean[] | Значение пользовательского свойства |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

Получает именованное целочисленное значение из пользовательских свойств.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для получения |
| value | int[] | Значение пользовательского свойства |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

Получает именованное значение DateTime из пользовательских свойств.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для получения |
| value | java.util.Date[] | Значение пользовательского свойства |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

Получает именованное строковое значение из пользовательских свойств.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для получения |
| value | java.lang.String[] | Значение пользовательского свойства |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

Получает именованное значение float из пользовательских свойств.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для получения |
| value | float[] | Значение пользовательского свойства |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

Получает именованное значение double из пользовательских свойств.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для получения |
| value | double[] | Значение пользовательского свойства |
| name | java.lang.String | Имя пользовательского свойства для получения. |
| value | double[] | Значение пользовательского свойства |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

Устанавливает именованное булево пользовательское свойство.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для установки |
| value | boolean | Значение пользовательского свойства |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

Устанавливает именованное целочисленное пользовательское свойство.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для установки |
| value | int | Значение пользовательского свойства |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

Устанавливает именованное пользовательское свойство DateTime.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для установки |
| value | java.util.Date | Значение пользовательского свойства |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

Устанавливает именованное строковое пользовательское свойство.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для установки |
| value | java.lang.String | Значение пользовательского свойства |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

Устанавливает именованное свойство типа float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для установки |
| value | float | Значение пользовательского свойства |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

Устанавливает именованное свойство типа double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя пользовательского свойства для установки |
| value | double | Значение пользовательского свойства |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
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

**Возвращаемое значение:**
com.aspose.slides.ISensitivityLabel[]