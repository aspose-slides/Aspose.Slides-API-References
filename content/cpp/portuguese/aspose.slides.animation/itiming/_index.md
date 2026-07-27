---
title: ITiming
second_title: Referência da API Aspose.Slides para C++
description: Representa o tempo da animação.
type: docs
weight: 443
url: /pt/aspose.slides.animation/itiming/
---
## ITiming classe

Representa o tempo da animação.

```cpp
class ITiming : public virtual System::Object
```

## Métodos

| Method | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual **float** [get_Accelerate](./get_accelerate/)() | Descreve a porcentagem da duração do efeito de aceleração de comportamento. Leia **float**. |
| virtual **bool** [get_AutoReverse](./get_autoreverse/)() | Descreve se a animação deve ser reproduzida automaticamente ao contrário após ser reproduzida na direção direta. Leia **bool**. |
| virtual **float** [get_Decelerate](./get_decelerate/)() | Descreve a porcentagem da duração do efeito de desaceleração de comportamento. Leia **float**. |
| virtual **float** [get_Duration](./get_duration/)() | Descreve a duração do efeito de animação. Leia **float**. |
| virtual **float** [get_RepeatCount](./get_repeatcount/)() | Descreve o número de vezes que o efeito deve ser repetido. Leia **float**. |
| virtual **float** [get_RepeatDuration](./get_repeatduration/)() | Descreve o número de vezes que o efeito deve ser repetido. Leia **float**. |
| virtual **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() | Este atributo especifica se o efeito será repetido até o final do slide. Leia **bool**. |
| virtual **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() | Este atributo especifica se o efeito será repetido até o próximo clique. Leia **bool**. |
| virtual [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() | Especifica se um efeito deve reiniciar após a conclusão. Leia [EffectRestartType](../effectrestarttype/). |
| virtual **bool** [get_Rewind](./get_rewind/)() | Este atributo especifica se o efeito será retrocedido quando a reprodução terminar. Leia **bool**. |
| virtual **float** [get_Speed](./get_speed/)() | Especifica a porcentagem pela qual acelerar (ou desacelerar) o tempo. Leia **float**. |
| virtual **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() | Descreve o tempo de atraso após o gatilho. Leia **float**. |
| virtual [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() | Descreve o tipo de gatilho. Leia [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_Accelerate](./set_accelerate/)(**float**) | Descreve a porcentagem da duração do efeito de aceleração de comportamento. Grave **float**. |
| virtual void [set_AutoReverse](./set_autoreverse/)(**bool**) | Descreve se a animação deve ser reproduzida automaticamente ao contrário após ser reproduzida na direção direta. Grave **bool**. |
| virtual void [set_Decelerate](./set_decelerate/)(**float**) | Descreve a porcentagem da duração do efeito de desaceleração de comportamento. Grave **float**. |
| virtual void [set_Duration](./set_duration/)(**float**) | Descreve a duração do efeito de animação. Grave **float**. |
| virtual void [set_RepeatCount](./set_repeatcount/)(**float**) | Descreve o número de vezes que o efeito deve ser repetido. Grave **float**. |
| virtual void [set_RepeatDuration](./set_repeatduration/)(**float**) | Descreve o número de vezes que o efeito deve ser repetido. Grave **float**. |
| virtual void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) | Este atributo especifica se o efeito será repetido até o final do slide. Grave **bool**. |
| virtual void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) | Este atributo especifica se o efeito será repetido até o próximo clique. Grave **bool**. |
| virtual void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) | Especifica se um efeito deve reiniciar após a conclusão. Grave [EffectRestartType](../effectrestarttype/). |
| virtual void [set_Rewind](./set_rewind/)(**bool**) | Este atributo especifica se o efeito será retrocedido ao término da reprodução. Grave **bool**. |
| virtual void [set_Speed](./set_speed/)(**float**) | Especifica a porcentagem pela qual acelerar (ou desacelerar) o tempo. Grave **float**. |
| virtual void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) | Descreve o tempo de atraso após o gatilho. Grave **float**. |
| virtual void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) | Descreve o tipo de gatilho. Grave [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [Object](../../system/object/)
* Namespace [Aspose::Slides::Animation](../)
* Biblioteca [Aspose.Slides](../../)