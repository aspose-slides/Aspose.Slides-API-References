---
title: FieldAttributes
second_title: Aspose.Slides para C++ – Referência da API
description: Atributos de campo refletidos.
type: docs
weight: 170
url: /pt/system.reflection/fieldattributes/
---
## FieldAttributes enum

Atributos de campo refletidos.

```cpp
enum class FieldAttributes
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| FieldAccessMask | 7 | Máscara de acesso ao membro. Use esta máscara para recuperar informações de acessibilidade. |
| PrivateScope | 0 | Membros não referenciáveis. |
| Private | 1 | Membros privados. |
| FamANDAssem | 2 | Membros privados e de escopo de assembly. |
| Assembly | 3 | Membros de escopo de assembly. |
| Family | 4 | Membros acessíveis por tipo e subtipos. |
| FamORAssem | 5 | Membros acessíveis por tipo, subtipos e assembly. |
| Public | 6 | Membros acessíveis por qualquer pessoa. |
| Static | 16 | Membros estáticos, em oposição a membros de instância. |
| InitOnly | 32 | Membros const que podem ser inicializados apenas, mas não alterados. |
| Literal | 64 | Membros constantes em tempo de compilação. |
| NotSerialized | 128 | Membros não serializados. |
| SpecialName | 512 | Campo especial de um dos nomes abaixo. |
| PinvokeImpl | 8192 | Implementação encaminhada de interop. |
| ReservedMask | 38144 | Sinalizadores reservados apenas para uso em tempo de execução. |
| RTSpecialName | 1024 | O runtime deve verificar a codificação do nome. |
| HasFieldMarshal | 4096 | Informação de marshaling está presente. |
| HasDefault | 32768 | Valor padrão está presente. |
| HasFieldRVA | 256 | RVA está presente. |

## Veja Também

* Espaço de nomes [System::Reflection](../)
* Biblioteca [Aspose.Slides](../../)