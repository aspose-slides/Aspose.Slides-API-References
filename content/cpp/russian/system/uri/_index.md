---
title: Uri
second_title: Справочник API Aspose.Slides для C++
description: "Унифицированный идентификатор ресурса. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его функциям в качестве аргумента."
type: docs
weight: 1366
url: /ru/system/uri/
---
## Класс Uri


Унифицированный идентификатор ресурса. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../smartptr/) и используйте этот указатель для передачи его функциям в качестве аргумента.

```cpp
class Uri : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | Определяет тип указанного имени хоста. |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | Определяет, является ли указанная схема действительной. |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | Сравнивает указанные объекты [Uri](./) с использованием указанных правил сравнения. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | Определяет, равны ли URI, представленные текущим и указанным объектами. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | Преобразует строку в её экранированное представление. |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | Преобразует строку URI в её экранированное представление. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | Получает десятичное значение шестнадцатеричной цифры. |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | Возвращает абсолютный путь URI. |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | Возвращает абсолютный URI. |
| [String](../string/) [get_Authority](./get_authority/)() const | Возвращает имя хоста и номер порта сервера. |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | Возвращает неэкранированное имя хоста. |
| [String](../string/) [get_Fragment](./get_fragment/)() const | Возвращает экранированный фрагмент URI. |
| [String](../string/) [get_Host](./get_host/)() const | Возвращает имя хоста. |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | Возвращает тип имени хоста. |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | Возвращает международное доменное имя хоста. |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | Определяет, является ли URI, представленный текущим объектом, абсолютным. |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | Определяет, имеет ли URI, представленный текущим объектом, порт по умолчанию для схемы URI. |
| **bool** [get_IsFile](./get_isfile/)() const | Определяет, является ли URI, представленный текущим объектом, файлом. |
| **bool** [get_IsLoopback](./get_isloopback/)() const | Определяет, ссылается ли URI, представленный текущим объектом, на локальный хост. |
| **bool** [get_IsUnc](./get_isunc/)() const | Определяет, является ли URI, представленный текущим объектом, путем UNC. |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | Возвращает представление имени файла, на которое ссылается URI текущего объекта, в виде представления ОС. |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | Возвращает строку URI, переданную конструктору при создании текущего объекта. |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | Возвращает абсолютный путь и компоненты запроса URI, представленного текущим объектом, разделённые знаком вопроса (?). |
| **int32_t** [get_Port](./get_port/)() const | Возвращает номер порта URI, представленного текущим объектом. |
| [String](../string/) [get_Query](./get_query/)() const | Возвращает информацию запроса, включённую в URI, представленный текущим объектом. |
| [String](../string/) [get_Scheme](./get_scheme/)() const | Возвращает схему URI, представленного текущим объектом. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | Возвращает массив строк, содержащих сегменты пути URI, представленного текущим объектом. |
| **bool** [get_UserEscaped](./get_userescaped/)() const | Определяет, была ли строка URI, переданная конструктору текущего объекта, полностью экранирована. |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | Возвращает имя пользователя, пароль и другую пользовательскую информацию, связанную с URI, представленным текущим объектом. |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | Возвращает указанные компоненты URI, представленного текущим объектом, с использованием указанного экранирования. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Получает хеш-код URI. |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | Возвращает указанную часть URI, представленного текущим объектом. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../object/gettype/). |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | Возвращает шестнадцатеричный эквивалент указанного символа. |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | Преобразует указанное шестнадцатеричное представление символа в символ. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | Определяет, является ли URI, представленный текущим объектом [Uri](./), базой URI, представленного указанным объектом [Uri](./). |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | Определяет, представляет ли указанный символ действительную шестнадцатеричную цифру. |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | Определяет, закодирован ли символ в указанной строке на указанной позиции в шестнадцатеричном виде. |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | Указывает, является ли строка, использованная для создания этого [Uri](./), корректно сформированной и не требует дальнейшего экранирования. |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | Определяет, является ли указанная строка корректно сформированным URI. |
| void [Lock](../object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../lockcontext/). |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Определяет разницу между двумя экземплярами [Uri](./). |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Определяет разницу между URI, представленными текущим и указанным объектами [Uri](./). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../object/object/)([Object](../object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Специализация [Object::ReferenceEquals](../object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Возвращает строковое представление URI, представленного текущим объектом. |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Создаёт объект [Uri](./), представляющий указанный URI; аргумент указывает тип URI. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Создаёт объект [Uri](./) из указанного объекта [Uri](./), представляющего базовый URI, и строкового представления относительного URI. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Создаёт объект [Uri](./) из указанных базового и относительного URI. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Реализует конструкцию C# typeof([System.Object](../object/)). |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | Разэкранивает указанную экранированную строку. |
| void [Unlock](../object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../lockcontext/). |
|  [Uri](./uri/)(const [String](../string/)\&) | Создаёт объект [Uri](./), представляющий указанный URI. |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | Создаёт объект [Uri](./), представляющий указанный URI; аргумент указывает, следует ли экранировать URI. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | Создаёт объект [Uri](./) из указанного объекта [Uri](./), представляющего базовый URI, и строкового представления относительного URI; аргумент указывает, следует ли экранировать URI. |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | Создаёт объект [Uri](./), представляющий указанный URI; аргумент указывает тип URI. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | Создаёт объект [Uri](./) из указанных базового и относительного URI. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Создаёт объект [Uri](./) из указанных базового и относительного URI. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../object/~object/)() | Уничтожает объект. Очищает все внутренние структуры данных. |

## Поля

| Поле | Описание |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | Указывает символы, разделяющие схему протокола связи и часть адреса [Uri](./). |
| static [UriSchemeFile](./urischemefile/) | Указывает, что [Uri](./) является указателем на файл. |
| static [UriSchemeFtp](./urischemeftp/) | Указывает, что [Uri](./) доступен через протокол FTP. |
| static [UriSchemeGopher](./urischemegopher/) | Указывает, что [Uri](./) доступен через протокол Gopher. |
| static [UriSchemeHttp](./urischemehttp/) | Указывает, что [Uri](./) доступен через протокол HTTP. |
| static [UriSchemeHttps](./urischemehttps/) | Указывает, что [Uri](./) доступен через протокол HTTPS. |
| static [UriSchemeMailto](./urischememailto/) | Указывает, что [Uri](./) является адресом электронной почты и доступен через протокол SMTP. |
| static [UriSchemeNetPipe](./urischemenetpipe/) | Указывает, что [Uri](./) доступен через схему NetPipe, используемую в [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNetTcp](./urischemenettcp/) | Указывает, что [Uri](./) доступен через схему NetTcp, используемую в [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNews](./urischemenews/) | Указывает, что [Uri](./) является интернет-группой новостей и доступен через протокол NNTP. |
| static [UriSchemeNntp](./urischemenntp/) | Указывает, что [Uri](./) является интернет-группой новостей и доступен через протокол NNTP. |

## Примечания



```cpp
#include "system/smart_ptr.h"
#include "system/uri.h"
#include <iostream>

int main()
{
  const auto uri = System::MakeObject<System::Uri>(u"https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/");

std::cout <<
  "AbsolutePath: " << uri->get_AbsolutePath() << std::endl <<
  "AbsoluteUri: " << uri->get_AbsoluteUri() << std::endl <<
  "Authority: " << uri->get_Authority() << std::endl <<
  "DnsSafeHost: " << uri->get_DnsSafeHost() << std::endl <<
  "Fragment: " << uri->get_Fragment() << std::endl <<
  "Host: " << uri->get_Host() << std::endl <<
  "IdnHost: " << uri->get_IdnHost() << std::endl <<
  "LocalPath: " << uri->get_LocalPath() << std::endl <<
  "OriginalString: " << uri->get_OriginalString() << std::endl <<
  "PathAndQuery: " << uri->get_PathAndQuery() << std::endl <<
  "Port: " << uri->get_Port() << std::endl <<
  "Query: " << uri->get_Query() << std::endl <<
  "Scheme: " << uri->get_Scheme() << std::endl;

  return 0;
}
/*
Этот пример кода выводит следующее:
AbsolutePath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
AbsoluteUri: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Authority: docs.codeporting.com
DnsSafeHost: docs.codeporting.com
Fragment:
Host: docs.codeporting.com
IdnHost: docs.codeporting.com
LocalPath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
OriginalString: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
PathAndQuery: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Port: 443
Query:
Scheme: https
*/
```

## См. также

* Класс [Object](../object/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)