---
title: ECDsaBotan
second_title: Aspose.Slides для C++ справка по API
description: "Алгоритм ECDsa в форме Botan. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 196
url: /ru/system.security.cryptography/ecdsabotan/
---
## ECDsaBotan класс

[ECDsa](../ecdsa/) алгоритм в форме Botan. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ECDsaBotan : public System::Security::Cryptography::ECDsa
```

## Методы

| Method | Description |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | Освобождает все ресурсы. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](../ecdsa/)\> [Create](../ecdsa/create/)() | Создаёт реализацию алгоритма ECDSA по умолчанию. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](../ecdsa/)\> [Create](../ecdsa/create/)(const [ECCurve](../eccurve/)\&) | Создаёт реализацию алгоритма ECDSA по умолчанию с только что созданным ключом над указанной кривой. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](../ecdsa/)\> [Create](../ecdsa/create/)(const [ECParameters](../ecparameters/)\&) | Создаёт реализацию алгоритма ECDSA по умолчанию, используя указанные параметры. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](../ecdsa/)\> [Create](../ecdsa/create/)(const [String](../../system/string/)\&) | Создаёт указанную реализацию алгоритма ECDSA. |
| void [Dispose](../asymmetricalgorithm/dispose/)() override | Освобождает ресурсы, принадлежащие текущему объекту. |
|  [ECDsaBotan](./ecdsabotan/)() | Конструктор. Использует параметры по умолчанию. |
|  [ECDsaBotan](./ecdsabotan/)(const [ECParameters](../ecparameters/)\&) | Конструктор. |
|  [ECDsaBotan](./ecdsabotan/)(const [ECCurve](../eccurve/)\&) | Конструктор. |
|  [ECDsaBotan](./ecdsabotan/)(**int32_t**) | Конструктор. |
|  [ECDsaBotan](./ecdsabotan/)(const Botan::ECDSA_PublicKey\&) | Конструктор. |
|  [ECDsaBotan](./ecdsabotan/)(const Botan::ECDSA_PrivateKey\&) | Конструктор. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa-значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| [ECParameters](../ecparameters/) [ExportExplicitParameters](./exportexplicitparameters/)(**bool**) override | Экспортирует явные параметры. |
| [ECParameters](../ecparameters/) [ExportParameters](./exportparameters/)(**bool**) override | Экспортирует именованные или явные параметры. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| void [FromXmlString](./fromxmlstring/)([String](../../system/string/)) override | Инициализирует объект, используя параметры в формате XML. Не реализовано. |
| void [FromXmlString](./fromxmlstring/)(const [String](../../system/string/)\&, [ECKeyXmlFormat](../eckeyxmlformat/)) | Инициализирует объект, используя параметры в формате XML. Не реализовано. |
| void [GenerateKey](./generatekey/)(const [ECCurve](../eccurve/)\&) override | Генерирует новую пару открытого/закрытого ключей для указанной кривой. |
| [HashAlgorithmName](../hashalgorithmname/) [get_HashAlgorithm](./get_hashalgorithm/)() const | Возвращает алгоритм хеширования. |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](../ecdsa/get_keyexchangealgorithm/)() override | Возвращает алгоритм обмена ключами. |
| virtual **int32_t** [get_KeySize](../asymmetricalgorithm/get_keysize/)() | Возвращает размер ключа. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | Возвращает массив допустимых размеров ключей. |
| [String](../../system/string/) [get_SignatureAlgorithm](../ecdsa/get_signaturealgorithm/)() override | Returns алгоритм подписи. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Возвращает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет вычислять хеш для пользовательских объектов. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Возвращает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| [ByteArrayPtr](../../system/bytearrayptr/) [HashData](./hashdata/)([ByteArrayPtr](../../system/bytearrayptr/), **int32_t**, **int32_t**, [HashAlgorithmName](../hashalgorithmname/)) override | Вычисляет хеш-значение указанного массива данных, используя указанный алгоритм хеширования. |
| [ByteArrayPtr](../../system/bytearrayptr/) [HashData](./hashdata/)([StreamPtr](../../system/streamptr/), [HashAlgorithmName](../hashalgorithmname/)) override | Вычисляет хеш-значение указанного бинарного потока, используя указанный алгоритм хеширования. |
| void [ImportParameters](./importparameters/)(const [ECParameters](../ecparameters/)\&) override | Импортирует все параметры из структуры данных. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со ссылкой nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_HashAlgorithm](./set_hashalgorithm/)(const [HashAlgorithmName](../hashalgorithmname/)\&) | Устанавливает алгоритм хеширования. |
| void [set_KeySize](./set_keysize/)(**int32_t**) override | Устанавливает размер ключа. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Возвращает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Вычисляет хеш-значение указанного массива данных и подписывает результат. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**) | Вычисляет хеш-значение указанного массива данных и подписывает результат. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&) | Вычисляет хеш-значение указанного бинарного потока и подписывает результат. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Вычисляет хеш-значение указанного массива данных, используя указанный алгоритм хеширования, и подписывает результат. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&) | Вычисляет хеш-значение указанного массива данных, используя указанный алгоритм хеширования, и подписывает результат. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Вычисляет хеш-значение указанного бинарного потока, используя указанный алгоритм хеширования, и подписывает результат. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) override | Вычисляет подпись указанного входного значения. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| [String](../../system/string/) [ToXmlString](./toxmlstring/)(**bool**) override | Экспортирует все параметры в формате XML. Не реализовано. |
| [String](../../system/string/) [ToXmlString](./toxmlstring/)([ECKeyXmlFormat](../eckeyxmlformat/)) | Экспортирует все параметры в формате XML. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Проверяет, что подпись указанных данных действительна. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Проверяет, что подпись указанных данных действительна. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Проверяет, что подпись указанного бинарного потока действительна. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Проверяет, что подпись указанных данных действительна. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Проверяет, что подпись указанных данных действительна. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Проверяет, что подпись указанного бинарного потока действительна. |
| **bool** [VerifyHash](./verifyhash/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/)) override | Проверяет подпись данных. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [ECDsa](../ecdsa/)
* Пространство имён [System::Security::Cryptography](../)
* Библиотека [Aspose.Slides](../../)