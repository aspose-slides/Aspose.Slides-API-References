---
title: BindingFlags
second_title: Referência da API Aspose.Slides para C++
description: Define modos de pesquisa de membros e tipos e ligações.
type: docs
weight: 157
url: /pt/system.reflection/bindingflags/
---
## BindingFlags enum

Define modos de pesquisa e ligações de membros e tipos.

```cpp
enum class BindingFlags
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Default | 0 | Sem opções especiais. |
| IgnoreCase | 1 | Ignora maiúsculas/minúsculas do nome ao procurar o item. |
| DeclaredOnly | 2 | Procura apenas membros declarados no tipo e não nos tipos base. |
| Instance | 4 | Procura entre os membros de instância. |
| Static | 8 | Procura entre os membros estáticos. |
| Public | 16 | Procura entre os membros públicos. |
| NonPublic | 32 | Procura entre os membros não públicos. |
| FlattenHierarchy | 64 | Procura entre os membros estáticos públicos e protegidos do tipo base. |
| InvokeMethod | 256 | Invoca o método. |
| CreateInstance | 512 | Cria uma instância do tipo refletido. |
| GetField | 1024 | Obtém o valor do campo. |
| SetField | 2048 | Define o valor do campo. |
| GetProperty | 4096 | Obtém o valor da propriedade. |
| SetProperty | 8192 | Define o valor da propriedade. |
| PutDispProperty | 16384 | Define a propriedade COM. |
| PutRefDispProperty | 32768 | Define a propriedade de referência COM. |
| ExactBinding | 65536 | A ligação de tipo deve ser exata, sem alterações de tipo. |
| SuppressChangeType | 131072 | Não suportado. |
| OptionalParamBinding | 262144 | Seleciona a sobrecarga com base na contagem de argumentos. |
| IgnoreReturn | 16777216 | Ignora o valor de retorno da interoperabilidade COM. |

## Ver também

* Espaço de nomes [System::Reflection](../)
* Biblioteca [Aspose.Slides](../../)