---
title: IPortionFormatEffectiveData
second_title: Справочник API Aspose.Slides для Java
description: Неизменяемый объект, содержащий свойства форматирования эффективной части текста.
type: docs
url: /ru/com.aspose.slides/iportionformateffectivedata/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

Неизменяемый объект, содержащий свойства форматирования эффективной части текста.

--------------------

Этот интерфейс используется совместно с интерфейсом [IPortionFormat](../../com.aspose.slides/iportionformat) для возврата эффективных значений форматирования с применением наследования.
## Методы

| Метод | Описание |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Возвращает идентификатор закладки. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Возвращает гиперссылку, определённую для клика мыши. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Возвращает гиперссылку, определённую для наведения мыши. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```


Возвращает идентификатор закладки. Только для чтения String.

**Возвращает:**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```


Возвращает гиперссылку, определённую для клика мыши. Только для чтения [IHyperlink](../../com.aspose.slides/ihyperlink).

**Возвращает:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```


Возвращает гиперссылку, определённую для наведения мыши. Только для чтения [IHyperlink](../../com.aspose.slides/ihyperlink).

**Возвращает:**
[IHyperlink](../../com.aspose.slides/ihyperlink)