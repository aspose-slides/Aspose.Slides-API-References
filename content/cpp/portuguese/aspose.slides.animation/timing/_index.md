---
title: Timing
second_title: Aspose.Slides para C++ Referência da API
description: Representa a temporização da animação.
type: docs
weight: 625
url: /pt/aspose.slides.animation/timing/
---
## Classe Timing

Representa a temporização da animação.

```cpp
class Timing : public Aspose::Slides::Animation::ITiming,
               public Aspose::Slides::IDOMObject
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if\<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| **float** [get_Accelerate](./get_accelerate/)() override | Descreve a porcentagem da duração do efeito de aceleração. Lê **float**. |
| **bool** [get_AutoReverse](./get_autoreverse/)() override | Descreve se a animação deve ser reproduzida automaticamente ao contrário após ser reproduzida na direção direta. Lê **bool**. |
| **float** [get_Decelerate](./get_decelerate/)() override | Descreve a porcentagem da duração do efeito de desaceleração. Lê **float**. |
| **float** [get_Duration](./get_duration/)() override | Descreve a duração do efeito de animação. Lê **float**. |
| **float** [get_RepeatCount](./get_repeatcount/)() override | Descreve o número de vezes que o efeito deve repetir. Lê **float**. |
| **float** [get_RepeatDuration](./get_repeatduration/)() override | Descreve o número de vezes que o efeito deve repetir. Lê **float**. |
| **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() override | Este atributo especifica se o efeito será repetido até o final do slide. Lê **bool**. |
| **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() override | Este atributo especifica se o efeito será repetido até o próximo clique. Lê **bool**. |
| [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() override | Especifica se um efeito deve reiniciar após a conclusão. Lê [EffectRestartType](../effectrestarttype/). |
| **bool** [get_Rewind](./get_rewind/)() override | Este atributo especifica se o efeito será rebobinado ao terminar a reprodução. Lê **bool**. |
| **float** [get_Speed](./get_speed/)() override | Especifica a porcentagem pela qual acelerar (ou desacelerar) o tempo. Lê **float**. |
| **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() override | Descreve o tempo de atraso após o gatilho. Lê **float**. |
| [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() override | Descreve o tipo de gatilho. Lê [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoga ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analoga à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analoga ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoga ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_Accelerate](./set_accelerate/)(**float**) override | Descreve a porcentagem da duração do efeito de aceleração. Grava **float**. |
| void [set_AutoReverse](./set_autoreverse/)(**bool**) override | Descreve se a animação deve ser reproduzida automaticamente ao contrário após reproduzir na direção direta. Grava **bool**. |
| void [set_Decelerate](./set_decelerate/)(**float**) override | Descreve a porcentagem da duração do efeito de desaceleração. Grava **float**. |
| void [set_Duration](./set_duration/)(**float**) override | Descreve a duração do efeito de animação. Grava **float**. |
| void [set_RepeatCount](./set_repeatcount/)(**float**) override | Descreve o número de vezes que o efeito deve repetir. Grava **float**. |
| void [set_RepeatDuration](./set_repeatduration/)(**float**) override | Descreve o número de vezes que o efeito deve repetir. Grava **float**. |
| void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) override | Este atributo especifica se o efeito será repetido até o final do slide. Grava **bool**. |
| void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) override | Este atributo especifica se o efeito será repetido até o próximo clique. Grava **bool**. |
| void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) override | Especifica se um efeito deve reiniciar após a conclusão. Grava [EffectRestartType](../effectrestarttype/). |
| void [set_Rewind](./set_rewind/)(**bool**) override | Este atributo especifica se o efeito será rebobinado ao terminar a reprodução. Grava **bool**. |
| void [set_Speed](./set_speed/)(**float**) override | Especifica a porcentagem pela qual acelerar (ou desacelerar) o tempo. Grava **float**. |
| void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) override | Descreve o tempo de atraso após o gatilho. Grava **float**. |
| void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) override | Descreve o tipo de gatilho. Grava [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para o modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; ao invés disso, use smart pointers ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; ao invés disso, use smart pointers ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoga ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; ao invés disso, use smart pointers ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; ao invés disso, use smart pointers ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Ver também

* Classe [ITiming](../itiming/)
* Classe [IDOMObject](../../aspose.slides/idomobject/)
* Namespace [Aspose::Slides::Animation](../)
* Biblioteca [Aspose.Slides](../../)