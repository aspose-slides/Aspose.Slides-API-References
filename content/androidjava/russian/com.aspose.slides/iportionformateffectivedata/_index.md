---
title: IPortionFormatEffectiveData
second_title: Aspose.Slides для Android через справку Java API
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

Этот интерфейс используется вместе с интерфейсом [IPortionFormat](../../com.aspose.slides/iportionformat) для возврата эффективных значений форматирования с учётом наследования.
## Методы

| Метод | Описание |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Возвращает идентификатор закладки. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Возвращает гиперссылку, определённую для щелчка мышью. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Возвращает гиперссылку, определённую при наведении мыши. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

Возвращает идентификатор закладки. Только для чтения String.

**Возвращаемое значение:**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```

Возвращает гиперссылку, определённую для щелчка мышью. Только для чтения [IHyperlink](../../com.aspose.slides/ihyperlink).

**Возвращаемое значение:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```

Возвращает гиперссылку, определённую при наведении мыши. Только для чтения [IHyperlink](../../com.aspose.slides/ihyperlink).

**Возвращаемое значение:**
[IHyperlink](../../com.aspose.slides/ihyperlink)