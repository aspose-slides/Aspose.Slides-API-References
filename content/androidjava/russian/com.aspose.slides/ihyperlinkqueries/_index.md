---
title: IHyperlinkQueries
second_title: Aspose.Slides для Android через Java API Reference
description: Обеспечивает простой доступ к содержащимся гиперссылкам.
type: docs
url: /ru/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Обеспечивает простой доступ к содержащимся гиперссылкам.

## Методы

| Метод | Описание |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Получить все вложенные объекты IHyperlinkContainer, содержащие ненулевой HyperlinkClick. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Получить все вложенные объекты IHyperlinkContainer, содержащие ненулевой HyperlinkMouseOver. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Получить все вложенные объекты IHyperlinkContainer, содержащие ненулевой HyperlinkMouseOver. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Удаляет все содержащиеся гиперссылки HyperlinkClick и HyperlinkMouseOver (во всех вложенных объектах IHyperlinkContainer). |

### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Получить все вложенные объекты IHyperlinkContainer, содержащие ненулевой HyperlinkClick. С заданным объектом IHyperlinkContainer вы можете управлять его гиперссылкой (чтение, обновление или удаление). См. интерфейс IHyperlinkContainer.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Все вложенные объекты IHyperlinkContainer, содержащие ненулевой HyperlinkClick

### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Получить все вложенные объекты IHyperlinkContainer, содержащие ненулевой HyperlinkMouseOver. С заданным объектом IHyperlinkContainer вы можете управлять его гиперссылкой (чтение, обновление или удаление). См. интерфейс IHyperlinkContainer.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Все вложенные объекты IHyperlinkContainer, содержащие ненулевой HyperlinkMouseOver

### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Получить все вложенные объекты IHyperlinkContainer, содержащие ненулевой HyperlinkMouseOver. С заданным объектом IHyperlinkContainer вы можете управлять его гиперссылкой (чтение, обновление или удаление). См. интерфейс IHyperlinkContainer.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Все вложенные объекты IHyperlinkContainer, содержащие ненулевой HyperlinkMouseOver

### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

Удаляет все содержащиеся гиперссылки HyperlinkClick и HyperlinkMouseOver (во всех вложенных объектах IHyperlinkContainer).