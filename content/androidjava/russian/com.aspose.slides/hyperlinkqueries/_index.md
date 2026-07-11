---
title: HyperlinkQueries
second_title: Aspose.Slides для Android через справочник Java API
description: Обеспечивает простой доступ к содержащимся гиперссылкам.
type: docs
url: /ru/com.aspose.slides/hyperlinkqueries/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries), com.aspose.slides.IDOMObject
```
public final class HyperlinkQueries implements IHyperlinkQueries, IDOMObject
```

Обеспечивает простой доступ к содержащимся гиперссылкам.
## Методы

| Метод | Описание |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Получить все подконтейнеры IHyperlinkContainer, содержащие ненулевой HyperlinkClick. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Получить все подконтейнеры IHyperlinkContainer, содержащие ненулевой HyperlinkMouseOver. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Получить все подконтейнеры IHyperlinkContainer, содержащие ненулевой HyperlinkMouseOver. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Удаляет все содержащиеся гиперссылки HyperlinkClick и HyperlinkMouseOver (во всех подконтейнерах IHyperlinkContainer). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```


Получить все подконтейнеры IHyperlinkContainer, содержащие ненулевой HyperlinkClick. С данным объектом IHyperlinkContainer вы можете управлять его гиперссылкой (чтение, обновление или удаление). См. интерфейс IHyperlinkContainer.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```


Получить все подконтейнеры IHyperlinkContainer, содержащие ненулевой HyperlinkMouseOver. С данным объектом IHyperlinkContainer вы можете управлять его гиперссылкой (чтение, обновление или удаление). См. интерфейс IHyperlinkContainer.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```


Получить все подконтейнеры IHyperlinkContainer, содержащие ненулевой HyperlinkMouseOver. С данным объектом IHyperlinkContainer вы можете управлять его гиперссылкой (чтение, обновление или удаление). См. интерфейс IHyperlinkContainer.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public final void removeAllHyperlinks()
```


Удаляет все содержащиеся гиперссылки HyperlinkClick и HyperlinkMouseOver (во всех подконтейнерах IHyperlinkContainer).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject