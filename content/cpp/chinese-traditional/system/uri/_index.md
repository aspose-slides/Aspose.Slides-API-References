---
title: Uri
second_title: Aspose.Slides for C++ API 參考
description: "統一資源標識符。此類的物件應僅使用 System::MakeObject() 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。始終將此類包裝成 System::SmartPtr 指標，並使用該指標將其作為參數傳遞給函式。"
type: docs
weight: 1392
url: /zh-hant/system/uri/
---
## Uri 類

統一資源標識符。此類的物件應僅使用 [System::MakeObject()](../makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。始終將此類包裝成 [System::SmartPtr](../smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。

```cpp
class Uri : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | 確定指定主機名稱的類型。 |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | 確定指定的方案是否有效。 |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | 使用指定的比較規則比較指定的 [Uri](./) 物件。 |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | 確定目前和指定物件所代表的 URI 是否相等。 |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | 使用 C# [Object.Equals](../object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | 將字串轉換為其轉義表示形式。 |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | 將 URI 字串轉換為其轉義表示形式。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | 取得十六進位數字的十進位值。 |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | 傳回 URI 的絕對路徑。 |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | 傳回絕對 URI。 |
| [String](../string/) [get_Authority](./get_authority/)() const | 傳回伺服器的主機名稱和埠號。 |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | 傳回未轉義的主機名稱。 |
| [String](../string/) [get_Fragment](./get_fragment/)() const | 傳回已轉義的 URI 片段。 |
| [String](../string/) [get_Host](./get_host/)() const | 傳回主機名稱。 |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | 傳回主機名稱類型。 |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | 傳回主機的國際化網域名稱。 |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | 確定目前物件所代表的 URI 是否為絕對。 |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | 確定目前物件所代表的 URI 的方案是否具有預設埠號。 |
| **bool** [get_IsFile](./get_isfile/)() const | 確定目前物件所代表的 URI 是否為檔案。 |
| **bool** [get_IsLoopback](./get_isloopback/)() const | 確定目前物件所代表的 URI 是否參照本機主機。 |
| **bool** [get_IsUnc](./get_isunc/)() const | 確定目前物件所代表的 URI 是否為 UNC 路徑。 |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | 傳回目前物件所代表的 URI 所參照檔案名稱的作業系統表示。 |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | 傳回在建構目前物件時傳入建構函式的 URI 字串。 |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | 傳回目前物件所代表的 URI 的絕對路徑與查詢組件，兩者以問號 (?) 分隔。 |
| **int32_t** [get_Port](./get_port/)() const | 傳回目前物件所代表的 URI 的埠號。 |
| [String](../string/) [get_Query](./get_query/)() const | 傳回目前物件所代表的 URI 中包含的查詢資訊。 |
| [String](../string/) [get_Scheme](./get_scheme/)() const | 傳回目前物件所代表的 URI 的方案。 |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | 傳回包含目前物件所代表的 URI 路徑段的字串陣列。 |
| **bool** [get_UserEscaped](./get_userescaped/)() const | 確定傳入目前物件建構函式的 URI 字串是否已完整轉義。 |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | 傳回與目前物件所代表的 URI 相關的使用者名稱、密碼和其他使用者資訊。 |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | 使用指定的轉義方式傳回目前物件所代表的 URI 的指定組件。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 取得 URI 的雜湊碼。 |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | 傳回目前物件所代表的 URI 的指定部分。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../object/gettype/) 呼叫。 |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | 傳回指定字元的十六進位等價字元。 |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | 將指定的十六進位字元表示轉換為字元。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 檢查物件是否代表 targetType 所描述的型別實例。相當於 C# 'is' 運算子。 |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | 確定目前 [Uri](./) 物件所代表的 URI 是否為指定 [Uri](./) 物件所代表的 URI 的基礎。 |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | 確定指定字元是否為有效的十六進位數字。 |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | 確定指定字串中指定位置的字元是否為十六進位編碼。 |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | 指示用於建構此 [Uri](./) 的字串是否符合良好格式且不需要再進一步轉義。 |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | 確定指定字串是否為格式良好的 URI。 |
| void [Lock](../object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../lockcontext/) 哨兵物件。 |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 確定兩個 [Uri](./) 實例之間的差異。 |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 確定目前物件與指定 [Uri](./) 物件所代表的 URI 之間的差異。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../object/object/)([Object](../object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) 的特殊化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) 的特殊化，用於字串的情況。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| [String](../string/) [ToString](./tostring/)() const override | 傳回目前物件所代表的 URI 的字串表示形式。 |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 構造一個表示指定 URI 的 [Uri](./) 物件；參數指定 URI 類型。 |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 從表示基礎 URI 的指定 [Uri](./) 物件與相對 URI 的字串表示，構造一個 [Uri](./) 物件。 |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 從指定的基礎和相對 URI 構造一個 [Uri](./) 物件。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | 實作 C# typeof([System.Object](../object/)) 建構式。 |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | 將指定的已轉義字串解除轉義。 |
| void [Unlock](../object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../lockcontext/) 哨兵物件。 |
|  [Uri](./uri/)(const [String](../string/)\&) | 構造一個表示指定 URI 的 [Uri](./) 物件。 |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | 構造一個表示指定 URI 的 [Uri](./) 物件；參數指定是否應轉義該 URI。 |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | 從表示基礎 URI 的指定 [Uri](./) 物件與相對 URI 的字串表示，構造一個 [Uri](./) 物件；參數指定是否應轉義該 URI。 |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | 構造一個表示指定 URI 的 [Uri](./) 物件；參數指定 URI 類型。 |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | 從指定的基礎和相對 URI 構造一個 [Uri](./) 物件。 |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | 從指定的基礎和相對 URI 構造一個 [Uri](./) 物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual  [~Object](../object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 欄位

| 欄位 | 描述 |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | 指定在通訊協定方案與 [Uri](./) 的地址部分之間分隔的字元。 |
| static [UriSchemeFile](./urischemefile/) | 指定 [Uri](./) 為指向檔案的指標。 |
| static [UriSchemeFtp](./urischemeftp/) | 指定 [Uri](./) 透過檔案傳輸協定存取。 |
| static [UriSchemeGopher](./urischemegopher/) | 指定 [Uri](./) 透過 Gopher 協定存取。 |
| static [UriSchemeHttp](./urischemehttp/) | 指定 [Uri](./) 透過超文字傳輸協定 (HTTP) 存取。 |
| static [UriSchemeHttps](./urischemehttps/) | 指定 [Uri](./) 透過安全超文字傳輸協定 (HTTPS) 存取。 |
| static [UriSchemeMailto](./urischememailto/) | 指定 [Uri](./) 為電子郵件位址，並透過簡易郵件傳輸協定存取。 |
| static [UriSchemeNetPipe](./urischemenetpipe/) | 指定 [Uri](./) 透過 [Windows](../../system.windows/) 通訊基礎結構使用的 NetPipe 方案存取。 |
| static [UriSchemeNetTcp](./urischemenettcp/) | 指定 [Uri](./) 透過 [Windows](../../system.windows/) 通訊基礎結構使用的 NetTcp 方案存取。 |
| static [UriSchemeNews](./urischemenews/) | 指定 [Uri](./) 為網際網路新聞群組，並透過網路新聞傳輸協定存取。 |
| static [UriSchemeNntp](./urischemenntp/) | 指定 [Uri](./) 為網際網路新聞群組，並透過網路新聞傳輸協定存取。 |

## 備註

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
此程式碼範例會產生以下輸出:
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

## 另見

* 類 [Object](../object/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)