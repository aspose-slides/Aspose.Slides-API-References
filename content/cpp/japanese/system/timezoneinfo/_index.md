---
title: TimeZoneInfo
second_title: Aspose.Slides for C++ API リファレンス
description: "特定のタイムゾーンを記述する情報を表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないとランタイムエラーやアサーションフォルトが発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数への引数として使用してください。"
type: docs
weight: 1340
url: /ja/system/timezoneinfo/
---
## TimeZoneInfo クラス

特定のタイムゾーンを記述する情報を表します。このクラスのオブジェクトは [System::MakeObject()](../makeobject/) 関数を使用してのみ割り当てるべきです。スタック上または operator new を使用してこの型のインスタンスを作成しないでください。そうしないとランタイムエラーやアサーションフォルトが発生します。このクラスを [System::SmartPtr](../smartptr/) ポインタでラップし、そのポインタを関数への引数として渡すようにしてください。

```cpp
class TimeZoneInfo : public System::IEquatable<TimeZoneInfoPtr>
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static void [ClearCachedData](./clearcacheddata/)() | キャッシュされたタイムゾーンデータをクリアします。 |
| static [DateTime](../datetime/) [ConvertTime](./converttime/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&, const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) 時間をあるタイムゾーンから別のタイムゾーンへ変換します。 |
| static [DateTimeOffset](../datetimeoffset/) [ConvertTime](./converttime/)(const [DateTimeOffset](../datetimeoffset/)\&, const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) 時間を指定されたタイムゾーンの時間へ変換します。 |
| static [DateTime](../datetime/) [ConvertTime](./converttime/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) 時間を指定されたタイムゾーンの時間へ変換します。 |
| static [DateTime](../datetime/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)([DateTime](../datetime/), const [String](../string/)\&) | [Convert](../convert/) 時間を指定されたタイムゾーンの時間へ変換します。 |
| static [DateTimeOffset](../datetimeoffset/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)(const [DateTimeOffset](../datetimeoffset/)\&, const [String](../string/)\&) | [Convert](../convert/) 時間を指定されたタイムゾーンの時間へ変換します。 |
| static [DateTime](../datetime/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)([DateTime](../datetime/), const [String](../string/)\&, const [String](../string/)\&) | [Convert](../convert/) 時間を指定されたタイムゾーンの時間へ変換します。 |
| static [DateTime](../datetime/) [ConvertTimeFromUtc](./converttimefromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | UTC 時間を指定されたタイムゾーンの時間へ変換します。 |
| static [DateTime](../datetime/) [ConvertTimeToUtc](./converttimetoutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | 時間を UTC 時間に変換します。 |
| static [DateTime](../datetime/) [ConvertTimeToUtc](./converttimetoutc/)([DateTime](../datetime/)) | 時間を UTC 時間に変換します。 |
| static [DateTime](../datetime/) [ConvertTimeToUtcNoThrow](./converttimetoutcnothrow/)([DateTime](../datetime/)) | 時間を UTC 時間に変換します。FOR INTERNAL USE. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&, const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\>\&, **bool**) | カスタムタイムゾーンを作成します。 |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&, const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\>\&) | カスタムタイムゾーンを作成します。 |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&) | カスタムタイムゾーンを作成します。 |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override |  |
| **bool** [Equals](./equals/)([TimeZoneInfoPtr](../timezoneinfoptr/)) override | 現在のオブジェクトと指定されたオブジェクトが等しいかどうかを判定します。 |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) のセマンティクスでオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [FindSystemTimeZoneById](./findsystemtimezonebyid/)(const [String](../string/)\&) | 指定された識別子のタイムゾーンを取得します。 |
| [TimeSpan](../timespan/) [get_BaseUtcOffset](./get_baseutcoffset/)() const | 現在のタイムゾーンの標準時と UTC 時間との間の時間間隔を表す [TimeSpan](../timespan/) のインスタンスを返します。 |
| [String](../string/) [get_DaylightName](./get_daylightname/)() const | 現在のタイムゾーンのサマータイムの名前を取得します。 |
| [String](../string/) [get_DisplayName](./get_displayname/)() const | 現在のタイムゾーンの名前を取得します。 |
| [String](../string/) [get_Id](./get_id/)() const | 現在のオブジェクトが表すタイムゾーンの識別子を返します。 |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [get_Local](./get_local/)() | [TimeZoneInfo](./) のインスタンスを返します（ローカルタイムゾーンを表します）。 |
| [String](../string/) [get_StandardName](./get_standardname/)() const | 現在のタイムゾーンの標準時の名前を取得します。 |
| **bool** [get_SupportsDaylightSavingTime](./get_supportsdaylightsavingtime/)() const | タイムゾーンにサマータイム規則があるかどうかを示すフラグを取得します。 |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [get_Utc](./get_utc/)() | [TimeZoneInfo](./) のインスタンスを返します（UTC タイムゾーンを表します）。 |
| [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\> [GetAdjustmentRules](./getadjustmentrules/)() const | **AdjustmentRule** オブジェクトの配列を返します（現在の [TimeZoneInfo](./) オブジェクトに適用される調整規則を表します）。 |
| [ArrayPtr](../arrayptr/)\<[TimeSpan](../timespan/)\> [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)([DateTime](../datetime/)) const | 指定された日付と時刻がマッピングできる UTC の日付と時刻を取得します。 |
| [ArrayPtr](../arrayptr/)\<[TimeSpan](../timespan/)\> [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)(const [DateTimeOffset](../datetimeoffset/)\&) const | 指定された日付と時刻がマッピングできる UTC の日付と時刻を取得します。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| int [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| static [SharedPtr](../sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[TimeZoneInfoPtr](../timezoneinfoptr/)\>\> [GetSystemTimeZones](./getsystemtimezones/)() | ローカルシステムで利用可能なすべてのタイムゾーンのソート済みコレクションを取得します。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../object/gettype/) 呼び出しの類似です。 |
| [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)([DateTime](../datetime/)) const | 指定された日付と時刻に対して、このタイムゾーンと UTC タイムゾーンとの差分を計算します。 |
| [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)(const [DateTimeOffset](../datetimeoffset/)\&) const | 指定された日付と時刻に対して、このタイムゾーンと UTC タイムゾーンとの差分を計算します。 |
| static [TimeSpan](../timespan/) [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | 指定されたタイムゾーンの UTC 日時に対する UTC オフセットを返す内部ヘルパー関数です。FOR INTERNAL USE. |
| static [TimeSpan](../timespan/) [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&, **bool**\&, **bool**\&) | 指定されたタイムゾーンの UTC 日時に対する UTC オフセットを返す内部ヘルパー関数です。FOR INTERNAL USE. |
| [TimeSpan](../timespan/) [GetUtcOffsetNoThrow](./getutcoffsetnothrow/)([DateTime](../datetime/)) const | 指定された日付と時刻に対して、このタイムゾーンと UTC タイムゾーンとの差分を計算します。FOR INTERNAL USE. |
| **bool** [HasSameRules](./hassamerules/)(const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) const | 現在のタイムゾーンと別のタイムゾーンが同じ調整規則を持つかどうかをチェックします。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子の類似です。 |
| **bool** [IsAmbiguousTime](./isambiguoustime/)([DateTime](../datetime/)) const | 指定された日付と時刻が曖昧であり、複数の UTC 時間にマッピングできるかどうかをチェックします。 |
| **bool** [IsAmbiguousTime](./isambiguoustime/)(const [DateTimeOffset](../datetimeoffset/)\&) const | 指定された日付と時刻が曖昧であり、複数の UTC 時間にマッピングできるかどうかをチェックします。 |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)([DateTime](../datetime/)) const | 指定された日付と時刻がサマータイムの範囲に入っているかどうかをチェックします。 |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)(const [DateTimeOffset](../datetimeoffset/)\&) const | 指定された日付と時刻がサマータイムの範囲に入っているかどうかをチェックします。 |
| **bool** [IsDaylightSavingTimeNoThrow](./isdaylightsavingtimenothrow/)([DateTime](../datetime/)) const | 指定された日付と時刻がサマータイムの範囲に入っているかどうかをチェックします。 |
| **bool** [IsInvalidTime](./isinvalidtime/)([DateTime](../datetime/)) const | 指定された日付と時刻が無効かどうかをチェックします。 |
| void [Lock](../object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../object/object/)([Object](../object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウンタを減少させます。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../object/sharedcount/)() const | 共有参照カウントの現在値を取得します。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| [String](../string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static [DateTime](../datetime/) [TransitionTimeToDateTime](./transitiontimetodatetime/)(**int32_t**, const **TransitionTime**\&) | 年と **TransitionTime** を [DateTime](../datetime/) に変換するヘルパー関数です。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) 構文を実装します。 |
| void [Unlock](../object/unlock/)() | C# の lock() 文のアンロックを実装します。直接呼び出すか、[LockContext](../lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## タイプ定義

| タイプ定義 | 説明 |
| --- | --- |
| [AdjustmentRulePtr](./adjustmentruleptr/) | **AdjustmentRule** クラスのインスタンスへの共有ポインタのエイリアスです。 |

## 参照

* クラス [IEquatable](../iequatable/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)