---
title: MakeObject()
second_title: Referência da API Aspose.Slides para C++
description: Cria um objeto na heap e retorna um ponteiro compartilhado para ele.
type: docs
weight: 2887
url: /pt/system/makeobject/
---
## System::MakeObject(Args\&&...) função

Cria um objeto na heap e retorna um ponteiro compartilhado para ele.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Classe a ser instanciada. |
| Args | Tipos dos argumentos do construtor. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| args | Args\&&... | Argumentos do construtor. |

### Valor de retorno

[SmartPtr](../smartptr/) para o novo objeto criado, sempre em modo compartilhado.

## System::MakeObject(Args\&&...) função

Cria um objeto na heap e retorna um ponteiro compartilhado para ele.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [SmartPtr](../smartptr/) para a classe a ser instanciada. |
| Args | Tipos dos argumentos do construtor. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| args | Args\&&... | Argumentos do construtor. |

### Valor de retorno

[SmartPtr](../smartptr/) para o novo objeto criado, sempre em modo compartilhado.

## Veja também

* Classe [SmartPtr](../smartptr/)
* Estrutura [IsSmartPtr](../issmartptr/)
* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)