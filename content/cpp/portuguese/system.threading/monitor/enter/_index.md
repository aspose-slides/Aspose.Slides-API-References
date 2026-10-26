---
title: Enter()
second_title: Referência da API Aspose.Slides para C++
description: Adquire um bloqueio exclusivo em um objeto especificado.
type: docs
weight: 1
url: /pt/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) método


Adquire um bloqueio exclusivo em um objeto especificado.

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | O objeto no qual adquirir o bloqueio do monitor. |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) método


Adquire um bloqueio exclusivo no objeto especificado e define atomicamente um valor que indica se o bloqueio foi obtido.

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Monitor](../)
* Namespace [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)