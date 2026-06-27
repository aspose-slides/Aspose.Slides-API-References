---
title: SmartArtLayoutType
second_title: Aspose.Slides için .NET API Referansı
description: Bir SmartArt diyagramının düzen türünü temsil eder.
type: docs
weight: 10600
url: /tr/aspose.slides.smartart/smartartlayouttype/
---
## SmartArtLayoutType sayımı

Bir SmartArt diyagramının düzen türünü temsil eder.

```csharp
public enum SmartArtLayoutType
```

### Değerler

| İsim | Değer | Açıklama |
| --- | --- | --- |
| AccentProcess | `0` | Bir görev, süreç veya iş akışında ilerlemeyi, zaman çizelgesini veya ardışık adımları göstermek için kullanılır. Hem Level 1 hem de Level 2 metnini göstermede iyi çalışır. |
| AccentedPicture | `1` | Merkezi bir fotoğrafik fikri yanlarda ilgili fikirlerle göstermek için kullanılır. Üst Level 1 metni merkezi resmin üzerinde görünür. Diğer Level 1 şekiller için ilgili metinler küçük dairesel resimlerin yanında yer alır. Bu düzen metin olmadan da iyi çalışır. |
| AlternatingFlow | `2` | Bilgi gruplarını veya bir görev, süreç veya iş akışındaki ardışık adımları göstermek için kullanılır. Bilgi grupları arasındaki etkileşimi veya ilişkileri vurgular. |
| AlternatingHexagons | `3` | Birbiriyle bağlantılı fikirlerin serisini temsil etmek için kullanılır. Level 1 metni altıgenlerin içinde, Level 2 metni şekillerin dışında yer alır. |
| AlternatingPictureBlocks | `4` | Üstten alta belirli bir sıralama ile resimleri göstermek için kullanılır. Metin resmin sağında veya solunda dönüşümlü olarak yer alır. |
| AlternatingPictureCircles | `5` | Resim ve metin setini göstermek için kullanılır. İlgili metin merkezi dairelerde, resimler soldan sağa dönüşümlü olarak yer alır. |
| ArrowRibbon | `6` | Bağlantılı veya zıt kavramları, örneğin karşıt güçleri göstermek için kullanılır. İlk iki Level 1 satırı okların içinde metin olarak kullanılır. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| AscendingPictureAccentProcess | `7` | Açıklayıcı metinle artan bir resim serisini göstermek için kullanılır. Az miktarda metinle en iyi çalışır. |
| Balance | `8` | İki fikir arasındaki ilişkiyi veya karşılaştırmayı göstermek için kullanılır. İlk iki Level 1 satırının her biri merkez noktasının bir tarafının üst kısmındaki metne karşılık gelir. Level 2 metni her iki tarafta da dört şekle sınırlıdır. Denge, Level 2 metni içeren en çok şekle sahip tarafa kayar. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| BasicBendingProcess | `9` | Bir görev, süreç veya iş akışında ilerlemeyi veya ardışık adımları göstermek için kullanılır. Şekiller için hem yatay hem de dikey görüntü alanını maksimize eder. |
| BasicBlockList | `10` | Ardışık olmayan veya gruplanmış bilgi bloklarını göstermek için kullanılır. Şekiller için hem yatay hem de dikey görüntü alanını maksimize eder. |
| BasicChevronProcess | `11` | İlerlemeyi, zaman çizelgesini, ardışık adımları gösterir veya hareketi/yönü vurgular. Level 1 metni bir ok şeklinin içinde, Level 2 metni ok şekillerinin altında görünür. |
| BasicCycle | `12` | Döngüsel akışta aşamaların, görevlerin veya olayların devam eden bir dizisini temsil eder. Bağlayıcı oklar veya akış yerine aşamaları/vadileri vurgular. En iyi şekilde yalnızca Level 1 metniyle çalışır. |
| BasicMatrix | `13` | Dörtlüklerde bileşenlerin bir bütünle ilişkisini gösterir. İlk dört Level 1 satırı dörtlüklerde yer alır. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| BasicPie | `14` | Bireysel parçaların bir bütün oluşturma şeklini gösterir. İlk yedi Level 1 satırı eşit olarak dağıtılmış dilim veya pasta şekillerine karşılık gelir. Üst Level 1 şekli, vurgulamak için pastanın geri kalanının dışında yer alır. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| BasicProcess | `15` | Bir görev, süreç veya iş akışında ilerlemeyi veya ardışık adımları göstermek için kullanılır. |
| BasicPyramid | `16` | Orantılı, birbirine bağlı veya hiyerarşik ilişkileri, en büyük bileşeni altta ve yukarı doğru daralan şekilde gösterir. Level 1 metni piramit segmentlerinde, Level 2 metni her segmentin yanındaki şekillerde yer alır. |
| BasicRadial | `17` | Bir döngüde merkezi bir fikre olan ilişkiyi gösterir. İlk Level 1 satırı merkezi şekle, Level 2 metni çevredeki dairesel şekillere karşılık gelir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| BasicTarget | `18` | İçerme, geçişler veya hiyerarşik ilişkileri gösterir. İlk beş Level 1 satırı bir daireyle ilişkilidir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| BasicTimeline | `19` | Bir görev, süreç veya iş akışındaki ardışık adımları ya da zaman çizelgesi bilgilerini göstermek için kullanılır. Hem Level 1 hem de Level 2 metniyle iyi çalışır. |
| BasicVenn | `20` | Çakışan veya birbirine bağlı ilişkileri gösterir. İlk yedi Level 1 satırı bir daireyle ilişkilidir. Dört veya daha az Level 1 satırı varsa metin dairelerin içinde; daha fazlaysa dairelerin dışında yer alır. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| BendingPictureAccentList | `21` | Ardışık olmayan veya gruplanmış bilgi bloklarını göstermek için kullanılır. Küçük dairesel şekiller resimleri içerecek şekilde tasarlanmıştır. Hem Level 1 hem de Level 2 metniyle iyi çalışır. Şekiller için hem yatay hem de dikey görüntü alanını maksimize eder. |
| BendingPictureBlocks | `22` | Bir dizi resmi göstermek için kullanılır. Alt köşeyi kaplayan kutu az miktarda metin içerebilir. |
| BendingPictureCaption | `23` | Ardışık bir resim serisini göstermek için kullanılır. Alt köşeyi kaplayan kutu az miktarda metin içerebilir. |
| BendingPictureCaptionList | `24` | Bir dizi resmi göstermek için kullanılır. Başlık ve açıklama her resmin altında bir açıklama şekli içinde görünür. |
| BendingPictureSemiTransparentText | `25` | Bir dizi resmi göstermek için kullanılır. Yarı şeffaf bir kutu resmin alt kısmını kaplar ve tüm metin seviyelerini içerir. |
| BlockCycle | `26` | Döngüsel akışta aşamaların, görevlerin veya olayların devam eden bir dizisini temsil eder. Bağlayıcı oklar veya akış yerine aşamaları/vadileri vurgular. |
| BubblePictureList | `27` | Bir dizi resmi göstermek için kullanılır. En fazla sekiz Level 1 resmi içerebilir. Kullanılmayan metin ve resimler görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. Az miktarda metinle en iyi çalışır. |
| CaptionedPictures | `28` | Çeşitli metin seviyelerine sahip resimleri göstermek için kullanılır. Az miktarda Level 1 ve orta miktarda Level 2 metinle en iyi çalışır. |
| ChevronList | `29` | Genel bir iş akışını oluşturan birkaç süreci gösteren bir ilerleme sağlar. Zıt süreçleri göstermek için de kullanılabilir. Level 1 metni soldaki ilk ok şekline, Level 2 metni ise Level 1 metni içeren her şeklin yatay alt adımlarına karşılık gelir. |
| CircleAccentTimeline | `30` | Olaylar veya zaman çizelgesi bilgileri serisini göstermek için kullanılır. Level 1 metni daha büyük dairesel şekillerin yanında, Level 2 metni daha küçük dairesel şekillerin yanında görünür. |
| CircleArrowProcess | `31` | Her öğe için destekleyici metinle ardışık öğeleri göstermek için kullanılır. Bu diyagram, az miktarda Level 1 metniyle en iyi çalışır. |
| CirclePictureHierarchy | `32` | Bir organizasyondaki hiyerarşik bilgi veya raporlama ilişkilerini göstermeye yarar. Resimler dairelerde, ilgili metin resimlerin yanında yer alır. |
| CircleRelationship | `33` | Merkezi bir fikirle olan ilişkiyi veya ondan gelen/alan ilişkiyi göstermek için kullanılır. Level 2 metni ardışık olmayan şekilde eklenir ve beş öğe ile sınırlıdır. Yalnızca bir Level 1 öğe bulunabilir. |
| CircularBendingProcess | `34` | Bir görev, süreç veya iş akışındaki uzun veya doğrusal olmayan bir dizi aşamayı gösterir. En iyi şekilde yalnızca Level 1 metniyle çalışır. Şekiller için hem yatay hem de dikey görüntü alanını maksimize eder. |
| CircularPictureCallout | `35` | Merkezi bir fikir ve alt fikirler veya ilgili öğeleri göstermek için kullanılır. İlk resmin metni resmin alt kısmını kaplar. Diğer Level 1 şekillerin ilgili metni küçük dairesel resimlerin yanında görünür. Bu diyagram metinsiz de iyi çalışır. |
| ClosedChevronProcess | `36` | Bir görev, süreç veya iş akışında ilerlemeyi, zaman çizelgesini veya ardışık adımları gösterir veya hareketi/yönü vurgular. Başlangıç şekline bilgi eklemek için kullanılabilir. En iyi şekilde yalnızca Level 1 metniyle çalışır. |
| ContinuousArrowProcess | `37` | Bir zaman çizelgesi veya bir görev, süreç ya da iş akışındaki ardışık adımları göstermek için kullanılır. En iyi şekilde Level 1 metniyle çalışır çünkü her Level 1 satırı ok şeklinin içinde yer alır. Level 2 metni ok şeklinin dışında görünür. |
| ContinuousBlockProcess | `38` | Bir görev, süreç veya iş akışında ilerlemeyi veya ardışık adımları göstermek için kullanılır. Az miktarda Level 1 ve Level 2 metniyle en iyi çalışır. |
| ContinuousCycle | `39` | Döngüsel akışta aşamaların, görevlerin veya olayların devam eden bir dizisini temsil eder. Tüm bileşenler arasındaki bağlantıyı vurgular. En iyi şekilde yalnızca Level 1 metniyle çalışır. |
| ContinuousPictureList | `40` | Birbirine bağlı bilgileri gruplamak için kullanılır. Dairesel şekiller resimleri içerecek şekilde tasarlanmıştır. |
| ConvergingArrows | `41` | Fikirleri veya kavramları merkezi bir noktada toplanacak şekilde göstermek için kullanılır. En iyi şekilde yalnızca Level 1 metniyle çalışır. |
| ConvergingRadial | `42` | Bir döngüde merkezi bir fikre kavram veya bileşen ilişkilerini göstermek için kullanılır. İlk Level 1 satırı merkezi dairesel şekle, Level 2 satırları çevredeki dikdörtgen şekillere karşılık gelir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| CounterbalanceArrows | `43` | İki zıt fikir veya kavramı göstermek için kullanılır. İlk iki Level 1 satırı bir oka karşılık gelir ve Level 2 metniyle iyi çalışır. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| CycleMatrix | `44` | Döngüsel bir ilerlemede merkezi bir fikre olan ilişkiyi gösterir. İlk dört Level 1 satırı dilim veya pasta şekline, Level 2 metni dilimin ya da pastanın yanındaki dikdörtgen şekle karşılık gelir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| DescendingBlockList | `45` | İlgili fikirleri veya bilgi listelerini gruplamak için kullanılır. Metin şekilleri yüksekliği ardışık olarak azaltır ve Level 1 metni dikey olarak görüntülenir. |
| DescendingProcess | `46` | Azalan bir olay serisini göstermek için kullanılır. İlk Level 1 metni oku üstte, son Level 1 metni oku altta görünür. Yalnızca ilk yedi Level 1 öğe gösterilir. Az-orta miktarda metinle en iyi çalışır. |
| DetailedProcess | `47` | Büyük miktarda Level 2 metniyle aşamaları göstermek için kullanılır. |
| DivergingArrows | `48` | Merkezi bir kaynaktan dışa doğru ilerleyen fikir veya kavramları göstermek için kullanılır. En iyi şekilde yalnızca Level 1 metniyle çalışır. |
| DivergingRadial | `49` | Bir döngüde merkezi bir fikre ilişkileri göstermek için kullanılır. İlk Level 1 satırı merkezi dairesel şekle karşılık gelir. Çevredeki daireler, merkezi fikri vurgular. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| Equation | `50` | Bir plan veya sonucu gösteren ardışık adımları veya görevleri göstermek için kullanılır. Son Level 1 satırı eşittir işaretinin (=) ardından görünür. En iyi şekilde yalnızca Level 1 metniyle çalışır. |
| FramedTextPicture | `51` | Resimleri karşılık gelen Level 1 metniyle çerçeve içinde göstermek için kullanılır. |
| Funnel | `52` | Bilgilerin filtrelenmesini veya parçaların bir bütün içinde birleşmesini göstermek için kullanılır. Sonuç vurgulanır. En fazla dört Level 1 satırı içerebilir; bu dört satırın sonuncusu hunenin altında, diğerleri dairesel şekille ilişkilidir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| Gear | `53` | Birbiriyle bağlantılı fikirleri göstermek için kullanılır. İlk üç Level 1 satırı dişli şekle, karşılık gelen Level 2 metni dişlinin yanındaki dikdörtgenlerde yer alır. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| GridMatrix | `54` | İki eksen boyunca kavramların yerleştirildiği bir gösterim sağlar. Bireysel bileşenleri bütün yerine vurgular. İlk dört Level 1 satırı dörtlüklerde yer alır. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| GroupedList | `55` | Bilgi grupları ve alt grupları ya da bir görev, süreç veya iş akışındaki adım ve alt adımları göstermek için kullanılır. Level 1 metni üst düzey yatay şekillere, Level 2 metni her ilgili üst düzey şeklin altındaki dikey alt adımlara karşılık gelir. Alt grupları, alt adımları, hiyerarşik bilgileri veya birden fazla bilgi listesini vurgulamak için iyidir. |
| HalfCircleOrganizationChart | `56` | Bir organizasyonda hiyerarşik bilgi veya raporlama ilişkilerini göstermek için kullanılır. Yardımcı şekiller ve Org Chart askı düzenleri bu düzenle mevcuttur. |
| HexagonCluster | `57` | Resimleri ilgili açıklayıcı metinle göstermek için kullanılır. Küçük altıgenler resim ve metin çiftini belirtir. Az miktarda metinle en iyi çalışır. |
| Hierarchy | `58` | Yukarıdan aşağıya doğru ilerleyen hiyerarşik ilişkileri göstermek için kullanılır. |
| HierarchyList | `59` | Gruplar içinde yukarıdan aşağıya ilerleyen hiyerarşik ilişkileri gösterir. Bilgi gruplamak veya listelemek için de kullanılabilir. |
| HorizontalBulletList | `60` | Ardışık olmayan veya gruplanmış bilgi listelerini göstermek için kullanılır. Büyük miktarda metinle iyi çalışır. Tüm metin aynı vurgulama seviyesindedir ve yön ima edilmez. |
| HorizontalHierarchy | `61` | Yatay olarak ilerleyen hiyerarşik ilişkileri göstermek için kullanılır. Karar ağaçları için iyidir. |
| HorizontalLabeledHierarchy | `62` | Yatay olarak ilerleyen ve hiyerarşik olarak gruplanan hiyerarşik ilişkileri gösterir. Başlık veya seviye 1 metnini vurgular. İlk Level 1 satırı hiyerarşinin başındaki şeklin içinde, ikinci ve sonraki satırlar uzun dikdörtgenlerin üstünde görünür. |
| HorizontalMultiLevelHierarchy | `63` | Yatay olarak ilerleyen büyük miktarda hiyerarşik bilgiyi göstermek için kullanılır. Hiyerarşinin üst kısmı dikey olarak görüntülenir. Bu düzen çok sayıda seviyeyi destekler. |
| HorizontalOrganizationChart | `64` | Yatay olarak hiyerarşik bilgi veya bir organizasyonda raporlama ilişkilerini göstermek için kullanılır. Yardımcı şekil ve Org Chart askı düzenleri bu düzenle mevcuttur. |
| HorizontalPictureList | `65` | Ardışık olmayan veya gruplanmış bilgiyi, ilgili resimlere vurgu yaparak göstermek için kullanılır. Üst şekiller resim barındıracak şekilde tasarlanmıştır. |
| IncreasingArrowsProcess | `66` | Bir süreçte ardışık ve çakışan adımları göstermek için kullanılır. En fazla beş Level 1 öğe içerir. Level 2 çok miktarda metin barındırabilir. |
| IncreasingCircleProcess | `67` | Her adımda dairenin içi artan bir adım serisini göstermek için kullanılır. En fazla yedi Level 1 adım, sınırsız Level 2 öğe vardır. Büyük miktarda Level 2 metniyle iyi çalışır. |
| InvertedPyramid | `68` | En büyük bileşen üstte, aşağı doğru daralan şekilde orantılı, birbirine bağlı veya hiyerarşik ilişkileri gösterir. Level 1 metni piramit segmentlerinde, Level 2 metni her segmentin yanındaki şekillerde yer alır. |
| LabeledHierarchy | `69` | Yukarıdan aşağıya doğru ilerleyen ve hiyerarşik olarak gruplanan hiyerarşik ilişkileri gösterir. Başlık veya seviye 1 metnini vurgular. İlk Level 1 satırı hiyerarşinin başındaki şeklin içinde, tüm sonraki satırlar uzun dikdörtgenlerin solunda görünür. |
| LinearVenn | `70` | Çakışan ilişkileri bir dizi içinde gösterir. En iyi şekilde yalnızca Level 1 metniyle çalışır. |
| LinedList | `71` | Kategorilere ve alt kategorilere ayrılmış büyük miktarda metni göstermek için kullanılır. Birden fazla metin seviyesiyle iyi çalışır. Aynı seviyedeki metinler çizgilerle ayrılmıştır. |
| MultidirectionalCycle | `72` | Her yönde gerçekleşebilen aşamaların, görevlerin veya olayların devam eden bir dizisini temsil eder. |
| NameandTitleOrganizationChart | `73` | Bir organizasyonda hiyerarşik bilgi veya raporlama ilişkilerini göstermek için kullanılır. Başlık kutusuna metin girmek için daha küçük dikdörtgen şeklin içinde doğrudan yazın. Yardımcı şekil ve Org Chart askı düzenleri bu düzenle mevcuttur. |
| NestedTarget | `74` | İçerme ilişkilerini göstermek için kullanılır. İlk üç Level 1 satırı şekillerin sol üst metnine karşılık gelir, Level 2 metni daha küçük şekillere karşılık gelir. En iyi şekilde minimal Level 2 metin satırlarıyla çalışır. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| NondirectionalCycle | `75` | Döngüsel akışta aşamaların, görevlerin veya olayların devam eden bir dizisini temsil eder. Tüm şekiller aynı öneme sahiptir. Yön belirtmenin gerekli olmadığı durumlarda iyidir. |
| OpposingArrows | `76` | İki zıt fikir veya merkezi bir noktadan ayrılan fikirleri göstermek için kullanılır. İlk iki Level 1 satırı bir oka karşılık gelir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| OpposingIdeas | `77` | İki zıt veya karşıt fikir gösterir. Bir veya iki Level 1 öğe bulunabilir. Her Level 1 metni birden çok alt seviyeye sahip olabilir. Büyük miktarda metinle iyi çalışır. |
| OrganizationChart | `78` | Bir organizasyonda hiyerarşik bilgi veya raporlama ilişkilerini göstermek için kullanılır. Yardımcı şekil ve Org Chart askı düzenleri bu düzenle mevcuttur. |
| PhasedProcess | `79` | Bir sürecin üç aşamasını göstermek için kullanılır. En fazla üç Level 1 öğe içerir. İlk iki Level 1 öğe her biri dört Level 2 öğe barındırabilir; üçüncü Level 1 öğe sınırsız sayıda Level 2 öğe barındırabilir. Az miktarda metinle en iyi çalışır. |
| PictureAccentBlocks | `80` | Köşeden başlayan bloklar içinde bir grup resmi göstermek için kullanılır. İlgili metin dikey olarak gösterilir. Başlık veya alt başlık slaytlarında vurgulama veya belge bölüm geçişleri için iyidir. |
| PictureAccentList | `81` | Gruplanmış veya ilgili bilgi gösterir. Üst köşelerdeki küçük şekiller resimleri barındırmak üzere tasarlanmıştır. Level 2 metni Level 1 metnine göre daha fazla vurgular ve büyük miktarda Level 2 metni için iyidir. |
| PictureAccentProcess | `82` | Bir görev, süreç veya iş akışındaki ardışık adımları göstermek için kullanılır. Arka plandaki dikdörtgen şekiller resimleri barındırmak üzere tasarlanmıştır. |
| PictureCaptionList | `83` | Ardışık olmayan veya gruplanmış bilgi bloklarını göstermek için kullanılır. Üst şekiller resim barındıracak şekilde tasarlanmıştır ve resimler metinden daha çok vurgulanır. Kısa açıklamalı resimler için iyidir. |
| PictureGrid | `84` | Resimleri kare bir ızgara üzerinde düzenlemek için kullanılır. Az miktarda Level 1 metni, resmin üstünde görünür. |
| PictureLineup | `85` | Yan yana bir dizi resmi göstermek için kullanılır. Level 1 metni resmin üstünü kaplar. Level 2 metni resmin altında görünür. |
| PictureStrips | `86` | Üstten alta doğru bir dizi resmi, her birinin yanında Level 1 metniyle göstermek için kullanılır. |
| PieProcess | `87` | Bir sürecin adımlarını, her bir pasta dilimi yedi şekle kadar büyüyerek gösterir. Level 1 metni dikey olarak gösterilir. |
| PlusandMinus | `88` | İki fikrin artı ve eksilerini göstermek için kullanılır. Her Level 1 metni birden çok alt seviyeye sahip olabilir. Büyük miktarda metinle iyi çalışır. En fazla iki Level 1 öğe içerir. |
| ProcessArrows | `89` | Bir süreci veya iş akışını gösteren bilgiler için kullanılır. Level 1 metni dairesel şekillerde, Level 2 metni ok şekillerinde görünür. Minimal metin ve hareket/yön vurgulamak için en iyisidir. |
| ProcessList | `90` | Bilgi grupları veya bir görev, süreç ya da iş akışındaki adım ve alt adımları göstermek için kullanılır. Level 1 metni üst yatay şekillere, Level 2 metni her ilgili üst düzey şeklin altındaki dikey alt adımlara karşılık gelir. |
| PyramidList | `91` | Orantılı, birbirine bağlı veya hiyerarşik ilişkileri gösterir. Metin piramit arka planının üzerindeki dikdörtgen şekillerde görünür. |
| RadialCluster | `92` | Merkezi bir fikir veya tema ile ilişkili verileri göstermek için kullanılır. Üst Level 1 metni merkezde, Level 2 metni çevredeki şekillerde görünür. En fazla yedi Level 2 şekil içerebilir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. Az miktarda metinle en iyi çalışır. |
| RadialCycle | `93` | Merkezi bir fikre ilişkin ilişkiyi gösterir. Hem merkez dairedaki hem de dış çemberdeki bilgileri vurgular. İlk Level 1 satırı merkezi daireye, Level 2 metni dış çemberdeki dairelere karşılık gelir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| RadialList | `94` | Merkezi bir fikre ilişkin ilişkileri bir döngü içinde göstermek için kullanılır. Merkez şekil bir resim içerebilir. Level 1 metni daha küçük dairelerde, ilgili Level 2 metni dairelerin yanında görünür. |
| RadialVenn | `95` | Hem çakışan ilişkileri hem de merkezi bir fikre olan ilişkiyi bir döngü içinde gösterir. İlk Level 1 satırı merkezi şekle, Level 2 satırları çevredeki dairesel şekillere karşılık gelir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| RandomToResultProcess | `96` | Bir dizi adım aracılığıyla kaotik fikirlerin nasıl birleşik bir hedefe veya fikre dönüşebileceğini göstermek için kullanılır. Birden çok Level 1 metni destekler, ancak ilk ve son Level 1 şekilleri sabittir. Az miktarda Level 1 ve orta miktarda Level 2 metinle en iyi çalışır. |
| RepeatingBendingProcess | `97` | Bir görev, süreç veya iş akışındaki ilerlemeyi veya ardışık adımları göstermek için kullanılır. Şekiller için hem yatay hem de dikey görüntü alanını maksimize eder. |
| ReverseList | `98` | İki öğe arasında geçiş yapmak için kullanılır. Yalnızca ilk iki metin öğesi görüntülenir ve her öğe büyük miktarda metin barındırabilir. İki öğe arasındaki değişikliği veya sıralama kaymasını göstermek için iyidir. |
| SegmentedCycle | `99` | Döngüsel akışta bir dizi aşama, görev veya olayı gösteren bir ilerleme sağlar. Birbirine bağlı parçaları vurgular. İlk yedi Level 1 satırı bir dilim veya pasta şekline karşılık gelir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| SegmentedProcess | `100` | Bir görev, süreç veya iş akışındaki ilerlemeyi veya ardışık adımları göstermek için kullanılır. Level 2 metni vurgulanır, çünkü her satır ayrı bir şekilde yer alır. |
| SegmentedPyramid | `101` | İçerme, orantılı veya birbirine bağlı ilişkileri gösterir. İlk dokuz Level 1 satırı üçgen şekillerde görünür. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. En iyi şekilde yalnızca Level 1 metniyle çalışır. |
| SnapshotPictureList | `102` | Resimleri açıklayıcı metinle göstermek için kullanılır. Level 2 metni bilgi listeleri içerebilir. Büyük miktarda metinle iyi çalışır. |
| SpiralPicture | `103` | En fazla beş resmi, karşılık gelen Level 1 başlıklarıyla merkeze doğru sarmal bir şekilde göstermek için kullanılır. |
| SquareAccentList | `104` | Kategorilere bölünmüş bilgi listelerini göstermek için kullanılır. Level 2 metni küçük kare şeklin yanında görünür. Büyük miktarda Level 2 metniyle iyi çalışır. |
| StackedList | `105` | Bilgi gruplarını veya bir görev, süreç ya da iş akışındaki adımları göstermek için kullanılır. Dairesel şekiller Level 1 metnini, ilgili dikdörtgenler Level 2 metnini içerir. Çok sayıda detay ve minimal Level 1 metin için iyidir. |
| StackedVenn | `106` | Çakışan ilişkileri gösterir. Büyümeyi veya geçişi vurgulamak için iyi bir seçimdir. En iyi şekilde yalnızca Level 1 metniyle çalışır. İlk yedi Level 1 satırı dairesel bir şekle karşılık gelir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| StaggeredProcess | `107` | Aşamalı bir aşağı doğru ilerlemeyi göstermek için kullanılır. İlk beş Level 1 satırı bir dikdörtgene karşılık gelir. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| StepDownProcess | `108` | Birden çok adım ve alt adım içeren aşağı doğru bir süreci göstermek için kullanılır. Az miktarda metinle en iyi çalışır. |
| StepUpProcess | `109` | Artan bir adım serisini veya bilgi listesini göstermek için kullanılır. |
| SubStepProcess | `110` | Her Level 1 metni arasında alt adımlar bulunan çok adımlı bir süreci göstermek için kullanılır. Az miktarda metinle en iyi çalışır ve yedi Level 1 adımla sınırlıdır. Her Level 1 adımı sınırsız alt adıma sahip olabilir. |
| TableHierarchy | `111` | Bilgiyi üstten alta doğru gruplar halinde ve her grup içinde hiyerarşileri gösterir. Bu düzen bağlayıcı çizgiler içermez. |
| TableList | `112` | Eş değerdeki gruplu veya ilgili bilgileri göstermek için kullanılır. İlk Level 1 satırı üst şekle, Level 2 metni sonraki listeler için kullanılır. |
| TargetList | `113` | Birbiriyle ilişkili veya çakışan bilgileri göstermek için kullanılır. İlk yedi Level 1 satırı dikdörtgen şekilde görünür. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. Hem Level 1 hem de Level 2 metinle iyi çalışır. |
| TextCycle | `114` | Döngüsel akışta aşamaların, görevlerin veya olayların devam eden bir dizisini temsil eder. Okları veya akışı aşamalardan ziyade vurgular. En iyi şekilde yalnızca Level 1 metniyle çalışır. |
| TitlePictureLineup | `115` | Her biri kendi başlığı ve açıklaması olan bir dizi resmi göstermek için kullanılır. Level 1 metni resmin üzerindeki kutuda, Level 2 metni resmin altında görünür. |
| TitledMatrix | `116` | Dört dörtlüğün bir bütünle ilişkisini göstermek için kullanılır. İlk Level 1 satırı merkezi şekle, ilk dört Level 2 satırı dörtlüklerde görünür. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| TitledPictureAccentList | `117` | Her Level 2 metni için bir vurgu resmi olan bilgi listelerini göstermek için kullanılır. Level 1 metni listenin üstündeki ayrı bir kutuda görüntülenir. |
| TitledPictureBlocks | `118` | Bir dizi resmi göstermek için kullanılır. Level 1 metni her resmin üstünde, Level 2 metni resmin yanında ve biraz üst üste gelir. |
| TrapezoidList | `119` | Eş değerdeki gruplanmış veya ilgili bilgileri göstermek için kullanılır. Büyük miktarda metinle iyi çalışır. |
| UpwardArrow | `120` | Bir görev, süreç veya iş akışında yukarı yönlü bir ilerleme veya adımları göstermek için kullanılır. İlk beş Level 1 satırı okun bir noktasına karşılık gelir. En az metinle en iyi çalışır. Kullanılmayan metin görünmez, ancak düzeni değiştirdiğinizde kullanılabilir. |
| VerticalAccentList | `121` | Bilgi listelerini göstermek için kullanılır. Level 2 metni dikey şeritlerin üzerindeki dikdörtgen şekillerde yer alır. Level 2 metni Level 1 metnine göre daha fazla vurgulanır ve orta miktarda Level 2 metni için iyi bir seçimdir. |
| VerticalArrowList | `122` | Ortak bir hedefe doğru ilerleyen bir görev, süreç veya iş akışındaki ardışık adımları göstermek için kullanılır. Bilgi madde listeleri için iyidir. |
| VerticalBendingProcess | `123` | Bir görev, süreç veya iş akışındaki ilerlemeyi veya ardışık adımları göstermek için kullanılır. Şekiller için hem yatay hem de dikey görüntü alanını maksimize eder. Yön veya hareketten çok şekiller arasındaki ilişkileri vurgular. |
| VerticalBlockList | `124` | Bilgi gruplarını veya bir görev, süreç ya da iş akışındaki adımları göstermek için kullanılır. Büyük miktarda Level 2 metniyle iyidir. Ana nokta ve birden çok alt nokta içeren metinler için iyi bir seçimdir. |
| VerticalBoxList | `125` | Özellikle büyük miktarda Level 2 metni içeren birkaç bilgi grubunu göstermek için kullanılır. Bilgi madde listeleri için iyi bir seçimdir. |
| VerticalBulletList | `126` | Ardışık olmayan veya gruplanmış bilgi bloklarını göstermek için kullanılır. Uzun başlıklar veya üst düzey bilgiler içeren listeler için iyidir. |
| VerticalChevronList | `127` | Bir görev, süreç veya iş akışındaki ilerlemeyi, ardışık adımları gösterir veya hareketi/yönü vurgular. Level 2 metni Level 1 metnine göre daha fazla vurgulanır ve büyük miktarda Level 2 metni için iyi bir seçimdir. |
| VerticalCircleList | `128` | Ardışık veya gruplanmış verileri göstermek için kullanılır. En iyi şekilde büyük dairesel şeklin yanında görünen Level 1 metniyle çalışır. Alt seviyeler daha küçük dairesel şekillerle ayrılır. |
| VerticalCurvedList | `129` | Eğri bir bilgi listesini göstermek için kullanılır. Vurgu dairesi şekillerine resim eklemek için resim doldurma uygulayın. |
| VerticalEquation | `130` | Plan veya sonucu gösteren ardışık adımları veya görevleri göstermek için kullanılır. Son Level 1 satırı ok sonrasında görünür. En iyi şekilde yalnızca Level 1 metniyle çalışır. |
| VerticalPictureAccentList | `131` | Ardışık olmayan veya gruplanmış bilgi bloklarını göstermek için kullanılır. Küçük daireler resim barındırmak üzere tasarlanmıştır. |
| VerticalPictureList | `132` | Ardışık olmayan veya gruplanmış bilgi bloklarını göstermek için kullanılır. Sol taraftaki küçük şekiller resim barındırmak üzere tasarlanmıştır. |
| VerticalProcess | `133` | Üstten alta doğru bir görev, süreç veya iş akışındaki ilerlemeyi gösterir. Düşük dikey alan nedeniyle en iyi şekilde Level 1 metniyle çalışır. |
| Custom | `134` | Özel bir düzen şablonuna sahip bir SmartArt diyagramını temsil eder |
| PictureOrganizationChart | `135` | Bir organizasyonda hiyerarşik bilgi veya raporlama ilişkilerini, karşılık gelen resimlerle göstermek için kullanılır. Yardımcı şekil ve Org Chart askı düzenleri bu düzenle mevcuttur. |

### Bakınız

* ad alanı [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->