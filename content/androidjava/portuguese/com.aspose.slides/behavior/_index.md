---
title: Behavior
second_title: Referência da API Java para Aspose.Slides for Android
description: Representa o comportamento da classe base do efeito.
type: docs
url: /pt/com.aspose.slides/behavior/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

Representa o comportamento da classe base do efeito.
## Métodos

| Método | Descrição |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Representa se os comportamentos de animação são acumulados. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Representa se os comportamentos de animação são acumulados. |
| [getAdditive()](#getAdditive--) | Representa se o comportamento de animação atual é combinado com outras animações em execução. |
| [setAdditive(int value)](#setAdditive-int-) | Representa se o comportamento de animação atual é combinado com outras animações em execução. |
| [getProperties()](#getProperties--) | Representa as propriedades do comportamento. |
| [getTiming()](#getTiming--) | Representa as propriedades de tempo para o comportamento de efeito. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Representa as propriedades de tempo para o comportamento de efeito. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```

Representa se os comportamentos de animação são acumulados. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```

Representa se os comportamentos de animação são acumulados. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```

Representa se o comportamento de animação atual é combinado com outras animações em execução. Leitura/Gravação [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Retorna:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```

Representa se o comportamento de animação atual é combinado com outras animações em execução. Leitura/Gravação [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```

Representa as propriedades do comportamento. Somente leitura [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Retorna:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

Representa as propriedades de tempo para o comportamento de efeito. Leitura/Gravação [ITiming](../../com.aspose.slides/itiming).

**Retorna:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

Representa as propriedades de tempo para o comportamento de efeito. Leitura/Gravação [ITiming](../../com.aspose.slides/itiming).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |