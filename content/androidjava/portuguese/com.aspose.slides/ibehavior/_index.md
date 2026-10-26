---
title: IBehavior
second_title: Aspose.Slides for Android via Java API Reference
description: Representa o comportamento da classe base do efeito.
type: docs
url: /pt/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Representa o comportamento da classe base do efeito.
## Métodos

| Método | Descrição |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Representa se os comportamentos de animação são acumulados. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Representa se os comportamentos de animação são acumulados. |
| [getAdditive()](#getAdditive--) | Representa se o comportamento de animação atual é combinado com outras animações em execução. |
| [setAdditive(int value)](#setAdditive-int-) | Representa se o comportamento de animação atual é combinado com outras animações em execução. |
| [getProperties()](#getProperties--) | Representa propriedades do comportamento. |
| [getTiming()](#getTiming--) | Representa propriedades de temporização para o comportamento do efeito. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Representa propriedades de temporização para o comportamento do efeito. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Representa se os comportamentos de animação são acumulados. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Representa se os comportamentos de animação são acumulados. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Representa se o comportamento de animação atual é combinado com outras animações em execução. Leitura/gravação [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Retorna:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Representa se o comportamento de animação atual é combinado com outras animações em execução. Leitura/gravação [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Representa propriedades do comportamento. Somente leitura [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Retorna:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Representa propriedades de temporização para o comportamento do efeito. Leitura/gravação [ITiming](../../com.aspose.slides/itiming).

**Retorna:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Representa propriedades de temporização para o comportamento do efeito. Leitura/gravação [ITiming](../../com.aspose.slides/itiming).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |