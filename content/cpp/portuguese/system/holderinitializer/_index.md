---
title: HolderInitializer
second_title: Referência da API Aspose.Slides para C++
description: Esta classe é usada para obter referência persistente à instância do objeto, seja ela um lvalue ou rvalue. Para obter tal referência, use o método 'HoldIfTemporary', que possui três sobrecargas. Duas delas recebem um rvalue como parâmetro e simplesmente retornam a referência a ele. A terceira, ao contrário, recebe um lvalue como parâmetro, faz uma cópia de ponteiro e então retorna a referência a essa cópia. Além disso, a classe tem o método 'Hold' para manter o valor passado incondicionalmente (usado para copiar valores de variáveis locais na pilha ou suas referências filhas).
type: docs
weight: 1639
url: /pt/system/holderinitializer/
---
## HolderInitializer struct

Esta classe é usada para obter referência persistente ao instância do objeto, seja ela um lvalue ou rvalue. Para obter tal referência, use o método 'HoldIfTemporary', que possui três sobrecargas. Duas delas recebem um rvalue como parâmetro e simplesmente retornam a referência a ele. A terceira, ao contrário, recebe um lvalue como parâmetro, faz uma cópia de ponteiro e então retorna a referência a essa cópia. Além disso, a classe possui o método 'Hold' para manter o valor passado incondicionalmente (usado para copiar valores de variáveis locais na pilha ou suas referências filhas).

```cpp
template<typename T,bool>class HolderInitializer
```

### Parâmetros do template

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo do objeto a ser mantido. |
| R | True, se T for um tipo de referência (especialização [SmartPtr](../smartptr/) ou tipo [System::String](../string/)), e a retenção de referências temporárias for realmente necessária, false - caso contrário. |

## Métodos

| Método | Descrição |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) | Copia o lvalue passado para o holder, então retorna a referência do holder. O chamador deve usar este método para manter o valor passado incondicionalmente. |
|  [HolderInitializer](./holderinitializer/)(T\&) | Inicializa a referência do holder com a passada. |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) | Retorna referência ao rvalue (const) |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&) | Retorna referência ao rvalue (não const) |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&&) | Copia o lvalue passado para o holder, então retorna a referência do holder. |

## Veja Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)