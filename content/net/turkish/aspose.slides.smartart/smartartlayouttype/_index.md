---
title: SmartArtLayoutType
second_title: Aspose.Sildes for .NET API Referansı
description: SmartArt diyagramının düzen tipini temsil eder.
type: docs
weight: 10640
url: /tr/aspose.slides.smartart/smartartlayouttype/
---
## SmartArtLayoutType enumeration

SmartArt diyagramının düzen türünü temsil eder.

```csharp
public enum SmartArtLayoutType
```

### Values

| Ad | Değer | Açıklama |
| --- | --- | --- |
| AccentProcess | `0` | Bir görev, süreç veya iş akışında bir ilerleme, zaman çizelgesi veya ardışık adımları göstermek için kullanılır. Hem Seviye 1 hem de Seviye 2 metni göstermede iyidir. |
| AccentedPicture | `1` | Merkezde fotoğrafik bir fikri ve yan tarafta ilgili fikirleri göstermek için kullanılır. Üst Seviye 1 metni merkezi resmin üzerinde görünür. Diğer Seviye 1 şekiller için karşılık gelen metin küçük dairesel resimlerin yanında görünür. Bu düzen metin olmadan da iyi çalışır. |
| AlternatingFlow | `2` | Bilgi gruplarını veya bir görev, süreç veya iş akışındaki ardışık adımları göstermek için kullanılır. Gruplar arasındaki etkileşimi veya ilişkileri vurgular. |
| AlternatingHexagons | `3` | Birbiriyle bağlantılı fikirler dizisini temsil etmek için kullanılır. Seviye 1 metni altıgenlerin içinde, Seviye 2 metni şekillerin dışında görünür. |
| AlternatingPictureBlocks | `4` | Üstten alta doğru bir dizi resim göstermek için kullanılır. Metin resmin sağında ya da solunda dönüşümlü olarak yer alır. |
| AlternatingPictureCircles | `5` | Metinle birlikte bir dizi resim göstermek için kullanılır. İlgili metin, resimlerin sol-sağ dönüşümlü bulunduğu merkezi dairelerde görünür. |
| ArrowRibbon | `6` | Bağlantılı veya zıt kavramları, örneğin zıt kuvvetleri, göstermek için kullanılır. Seviye 1 metninin ilk iki satırı okların içinde yer alır. Kullanılmayan metin görünmez, ancak düzen değiştirilirse kullanılabilir. |
| AscendingPictureAccentProcess | `7` | Açıklayıcı metinle birlikte yükselen bir resim serisini göstermek için kullanılır. Az miktarda metinle en iyi çalışır. |
| Balance | `8` | İki fikir arasındaki ilişkiyi karşılaştırmak veya göstermek için kullanılır. Seviye 1 metninin ilk iki satırı, merkezin bir yanındaki üstteki metne karşılık gelir. Seviye 2 metni, merkezin her iki yanında dört şekle sınırlıdır. Denge, Seviye 2 metni içeren en çok şekle doğru kayar. Kullanılmayan metin görünmez, ancak düzen değiştirilirse kullanılabilir. |
| BasicBendingProcess | `9` | Bir görev, süreç veya iş akışındaki ilerleme veya ardışık adımları göstermek için kullanılır. Şekiller için hem yatay hem de dikey alanı en üst düzeye çıkarır. |
| BasicBlockList | `10` | Sıra dışı veya gruplanmış bilgi bloklarını göstermek için kullanılır. Şekiller için hem yatay hem de dikey alanı en üst düzeye çıkarır. |
| BasicChevronProcess | `11` | İlerleme, zaman çizelgesi, bir görev, süreç veya iş akışındaki ardışık adımlar ya da hareket/direction vurgulamak için kullanılır. Seviye 1 metni bir ok şeklinde, Seviye 2 metni okların altında görünür. |
| BasicCycle | `12` | Dönerek akan bir dizi aşama, görev veya olayı temsil etmek için kullanılır. Bağlantı oklarından ziyade aşamaları vurgular. Yalnızca Seviye 1 metniyle en iyi çalışır. |
| BasicMatrix | `13` | Bileşenlerin bir bütünle ilişkisini dört bölgede gösterir. Seviye 1 metninin ilk dört satırı bölgelerde yer alır. Kullanılmayan metin görünmez, ancak düzen değiştirilirse kullanılabilir. |
| BasicPie | `14` | Bireysel parçaların bir bütün oluşturmasını gösterir. Seviye 1 metninin ilk yedi satırı eşit şekilde dağıtılmış dilim veya pasta şekilleriyle ilişkilidir. Üst Seviye 1 metin şekli, vurgulamak için pastanın dışındadır. Kullanılmayan metin görünmez, ancak düzen değiştirilirse kullanılabilir. |
| BasicProcess | `15` | Bir görev, süreç veya iş akışındaki ilerleme veya ardışık adımları göstermek için kullanılır. |
| BasicPyramid | `16` | En büyük bileşen alt kısımda, yukarı doğru daralan bir piramitle orantılı, birbirine bağlı veya hiyerarşik ilişkileri göstermek için kullanılır. Seviye 1 metni piramit segmentlerinde, Seviye 2 metni her segmentin yanındaki şekillerde görünür. |
| BasicRadial | `17` | Bir döngü içinde merkezi bir fikre olan ilişkiyi göstermek için kullanılır. Seviye 1 metninin ilk satırı merkezi şekle, Seviye 2 metni çevredeki dairesel şekillere karşılık gelir. Kullanılmayan metin görünmez, ancak düzen değiştirilirse kullanılabilir. |
| BasicTarget | `18` | İçerme, kademeler veya hiyerarşik ilişkileri göstermek için kullanılır. Seviye 1 metninin ilk beş satırı bir daireyle ilişkilidir. Kullanılmayan metin görünmez, ancak düzen değiştirilirse kullanılabilir. |
| BasicTimeline | `19` | Bir görev, süreç veya iş akışındaki ardışık adımları veya zaman çizelgesi bilgisini göstermek için kullanılır. Hem Seviye 1 hem de Seviye 2 metniyle iyi çalışır. |
| BasicVenn | `20` | Çakışan veya birbirine bağlı ilişkileri gösterir. Seviye 1 metninin ilk yedi satırı bir daireyle ilişkilidir. Dört veya daha az satır varsa metin dairelerin içinde, daha fazla satır varsa dairelerin dışında görünür. Kullanılmayan metin görünmez, ancak düzen değiştirilirse kullanılabilir. |
| BendingPictureAccentList | `21` | Sıra dışı veya gruplanmış bilgi bloklarını göstermek için kullanılır. Küçük dairesel şekiller resim barındırmak üzere tasarlanmıştır. Hem Seviye 1 hem de Seviye 2 metniyle iyi çalışır. Şekiller için hem yatay hem de dikey alanı en üst düzeye çıkarır. |
| BendingPictureBlocks | `22` | Bir dizi resmi göstermek için kullanılır. Alt köşeyi kapsayan kutu az miktarda metin barındırabilir. |
| BendingPictureCaption | `23` | Ardışık bir resim serisini göstermek için kullanılır. Alt köşeyi kapsayan kutu az miktarda metin barındırabilir. |
| BendingPictureCaptionList | `24` | Bir dizi resmi gösterir. Başlık ve açıklama, her resmin altında bir açıklama şekli içinde görünür. |
| BendingPictureSemiTransparentText | `25` | Bir dizi resmi gösterir. Resmin alt kısmını yarı saydam bir kutu kapsar ve tüm metin seviyelerini içerir. |
| BlockCycle | `26` | Dönerek akan bir dizi aşama, görev veya olayı temsil eder. Bağlantı oklarından ziyade aşamaları vurgular. |
| BubblePictureList | `27` | Bir dizi resmi gösterir. En fazla sekiz Seviye 1 resmi içerebilir. Kullanılmayan metin ve resimler görünmez, ancak düzen değiştirilirse kullanılabilir. Az miktarda metinle en iyi çalışır. |
| CaptionedPictures | `28` | Birden çok metin seviyesiyle resimleri gösterir. Az miktarda Seviye 1 ve orta miktarda Seviye 2 metinle en iyi çalışır. |
| ChevronList | `29` | Genel bir iş akışını oluşturan birkaç sürecin ilerlemesini gösterir. Ayrıca zıt süreçleri açıklamak için de kullanılabilir. Seviye 1 metni soldaki ilk ok şekliyle, Seviye 2 metni her şeklin alt adımlarıyla ilişkilidir. |
| CircleAccentTimeline | `30` | Bir dizi olay veya zaman çizelgesi bilgisini gösterir. Seviye 1 metni büyük dairesel şekillerin yanında, Seviye 2 metni daha küçük dairesel şekillerin yanında görünür. |
| CircleArrowProcess | `31` | Her öğe için destekleyici metinle ardışık öğeleri göstermek için kullanılır. Bu diyagram az miktarda Seviye 1 metniyle en iyi çalışır. |
| CirclePictureHierarchy | `32` | Bir organizasyondaki hiyerarşik bilgi veya raporlama ilişkilerini gösterir. Resimler dairelerde, ilgili metin resimlerin yanında görünür. |
| CircleRelationship | `33` | Merkezi bir fikir ile ilişkileri göstermek için kullanılır. Seviye 2 metin sıralı olmayan şekilde eklenir ve en fazla beş öğe ile sınırlıdır. Yalnızca bir Seviye 1 öğesi bulunabilir. |
| CircularBendingProcess | `34` | Uzun veya doğrusal olmayan bir görev, süreç veya iş akışı dizisini göstermek için kullanılır. Yalnızca Seviye 1 metniyle en iyi çalışır. Şekiller için hem yatay hem de dikey alanı en üst düzeye çıkarır. |
| CircularPictureCallout | `35` | Merkezi bir fikri ve alt-fikri ya da ilgili öğeleri gösterir. İlk resmin metni resmin alt kısmını kaplar. Diğer Seviye 1 şekillerin karşılık gelen metni küçük dairesel resimlerin yanında görünür. Bu diyagram metinsiz de iyi çalışır. |
| ClosedChevronProcess | `36` | Bir görev, süreç veya iş akışındaki ilerleme, zaman çizelgesi veya ardışık adımları göstermek, ya da hareket/direction vurgulamak için kullanılır. Başlangıç şeklinin içindeki bilgiyi vurgulamak için kullanılabilir. Yalnızca Seviye 1 metniyle en iyi çalışır. |
| ContinuousArrowProcess | `37` | Bir görev, süreç veya iş akışındaki zaman çizelgesi veya ardışık adımları göstermek için kullanılır. Her Seviye 1 metni satırı ok şeklinde içinde yer alır; Seviye 2 metni okların dışında görünür. |
| ContinuousBlockProcess | `38` | Bir görev, süreç veya iş akışındaki ilerleme veya ardışık adımları göstermek için kullanılır. Minimum Seviye 1 ve Seviye 2 metniyle en iyi çalışır. |
| ContinuousCycle | `39` | Dönerek akan bir dizi aşama, görev veya olayı temsil eder. Tüm bileşenler arasındaki bağlantıyı vurgular. Yalnızca Seviye 1 metniyle en iyi çalışır. |
| ContinuousPictureList | `40` | Birbirine bağlı bilgi gruplarını gösterir. Dairesel şekiller resim barındırmak üzere tasarlanmıştır. |
| ConvergingArrows | `41` | Merkez bir noktada buluşan fikir veya kavramları göstermek için kullanılır. Yalnızca Seviye 1 metniyle en iyi çalışır. |
| ConvergingRadial | `42` | Çevrim içinde merkezi bir fikre kavram veya bileşen ilişkilerini göstermek için kullanılır. Seviye 1 metninin ilk satırı merkezi dairesel şekle, Seviye 2 metni çevredeki dikdörtgensel şekillere karşılık gelir. Kullanılmayan metin görünmez, ancak düzen değiştirilirse kullanılabilir. |
| CounterbalanceArrows | `43` | İki zıt fikir veya kavramı göstermek için kullanılır. Seviye 1 metninin ilk iki satırı bir oka karşılık gelir ve Seviye 2 metniyle iyi çalışır. Kullanılmayan metin görünmez, ancak düzen değiştirilince kullanılabilir. |
| CycleMatrix | `44` | Döngüsel bir ilerlemede merkezi bir fikre ilişkiyi gösterir. Seviye 1 metninin ilk dört satırı bir dilim veya pasta şekline, Seviye 2 metni dilimin yanındaki dikdörtgen şekle karşılık gelir. Kullanılmayan metin görünmez, ancak düzen değiştirilirse kullanılabilir. |
| DescendingBlockList | `45` | İlgili fikir gruplarını veya bilgi listelerini göstermek için kullanılır. Metin şekilleri yüksekliği azalarak sıralanır ve Seviye 1 metni dikey olarak gösterilir. |
| DescendingProcess | `46` | Aşağı yönlü bir olay dizisini göstermek için kullanılır. İlk Seviye 1 metni okun üstünde, son Seviye 1 metni okun altında görünür. Sadece ilk yedi Seviye 1 öğesi gösterilir. Az-orta miktarda metinle en iyi çalışır. |
| DetailedProcess | `47` | Büyük miktarda Seviye 2 metniyle aşamalı ilerlemeyi göstermek için kullanılır. |
| DivergingArrows | `48` | Merkez bir kaynaktan dışa doğru ilerleyen fikir veya kavramları göstermek için kullanılır. Yalnızca Seviye 1 metniyle en iyi çalışır. |
| DivergingRadial | `49` | Çevrim içinde merkezi bir fikre ilişkileri göstermek için kullanılır. Seviye 1 metninin ilk satırı merkezi dairesel şekle karşılık gelir. Çevredeki daireleri, merkezi fikri değil, vurgular. Kullanılmayan metin görünmez, ancak düzen değiştirilirse kullanılabilir. |
| Equation | `50` | Bir plan veya sonucu gösteren ardışık adımları veya görevleri göstermek için kullanılır. Son Seviye 1 satırı eşittir (=) işaretinin ardından gelir. Yalnızca Seviye 1 metniyle en iyi çalışır. |
| FramedTextPicture | `51` | Resimleri, çerçeve içinde gösterilen ilgili Seviye 1 metniyle birlikte göstermek için kullanılır. |
| Funnel | `52` | Bilgi filtrelemeyi veya parçaların bir bütün haline gelmesini göstermek için kullanılır. Sonuç vurgulanır. En fazla dört Seviye 1 metin satırı içerebilir; bu satırlardan sonuncusu huninin altında, diğerleri dairesel şekille ilişkilidir. Kullanılmayan metin görünmez, ancak düzen değiştirilirse kullanılabilir. |
| Gear | `53` | Birbirine geçen fikirleri göstermek için kullanın. Seviye 1 metninin ilk üç satırı bir dişli şekline karşılık gelir ve bunlara karşılık gelen Seviye 2 metni dişli şeklinin yanındaki dikdörtgenlerde görünür. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde hâlâ kullanılabilir. |
| GridMatrix | `54` | İki eksen boyunca kavramların yerleşimini göstermek için kullanın. Bütün yerine bireysel bileşenleri vurgular. Seviye 1 metninin ilk dört satırı çeyreklerde görünür. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde hâlâ kullanılabilir. |
| GroupedList | `55` | Bilgi gruplarını ve alt gruplarını, ya da bir görev, süreç ya da iş akışındaki adımları ve alt adımları göstermek için kullanın. Seviye 1 metni üst düzey yatay şekillere, Seviye 2 metni ise her ilgili üst düzey şeklin altındaki dikey alt adımlara karşılık gelir. Alt grupları veya alt adımları, hiyerarşik bilgileri veya birden çok bilgi listesini vurgulamak için iyidir. |
| HalfCircleOrganizationChart | `56` | Bir organizasyondaki hiyerarşik bilgileri veya raporlama ilişkilerini göstermek için kullanın. Bu düzenle assistant shapes ve Org Chart hanging layouts mevcuttur. |
| HexagonCluster | `57` | İlgili açıklayıcı metinle birlikte resimleri göstermek için kullanın. Küçük altıgenler resim ve metin çiftini gösterir. Az miktarda metinle en iyi şekilde çalışır. |
| Hierarchy | `58` | Yukarıdan aşağıya doğru ilerleyen hiyerarşik ilişkileri göstermek için kullanın. |
| HierarchyList | `59` | Gruplar arasında ilerleyen hiyerarşik ilişkileri göstermek için kullanın. Ayrıca bilgiyi gruplamak veya listelemek için de kullanılabilir. |
| HorizontalBulletList | `60` | Sırasız veya gruplandırılmış bilgi listelerini göstermek için kullanın. Çok miktarda metinle iyi çalışır. Tüm metin aynı vurgu seviyesine sahiptir ve yön ima edilmez. |
| HorizontalHierarchy | `61` | Yatay olarak ilerleyen hiyerarşik ilişkileri göstermek için kullanın. Karar ağaçları için iyidir. |
| HorizontalLabeledHierarchy | `62` | Yatay ilerleyen ve hiyerarşik olarak gruplandırılmış ilişkileri göstermek için kullanın. Başlık veya seviye 1 metnini vurgular. Seviye 1 metninin ilk satırı hiyerarşinin başlangıcındaki şekilde görünür, ikinci ve sonraki tüm satırlar uzun dikdörtgenlerin üst kısmında görünür. |
| HorizontalMultiLevelHierarchy | `63` | Yatay olarak ilerleyen büyük miktarda hiyerarşik bilgiyi göstermek için kullanın. Hiyerarşinin üst kısmı dikey olarak görüntülenir. Bu düzen hiyerarşide birçok seviyeyi destekler. |
| HorizontalOrganizationChart | `64` | Bir organizasyonda hiyerarşik bilgi veya raporlama ilişkilerini yatay olarak veya göstermek için kullanın. Bu düzenle assistant shape ve Org Chart hanging layouts mevcuttur. |
| HorizontalPictureList | `65` | İlgili resimlere vurgu yaparak sırasız veya gruplandırılmış bilgiyi göstermek için kullanın. Üst şekiller resim içerecek şekilde tasarlanmıştır. |
| IncreasingArrowsProcess | `66` | Bir süreçte sıralı ve üst üste gelen adımları göstermek için kullanın. Beş Seviye 1 öğeyle sınırlıdır. Seviye 2 büyük miktarda metin içerebilir. |
| IncreasingCircleProcess | `67` | Her adımda dairenin iç kısmı artan adım serisini göstermek için kullanın. Yedi Seviye 1 adımla sınırlıdır, ancak Seviye 2 öğeleri sınırsızdır. Seviye 2 metninin büyük miktarlarıyla iyi çalışır. |
| InvertedPyramid | `68` | En büyük bileşen üstte ve daralan bir yapıda orantılı, birbirine bağlı veya hiyerarşik ilişkileri göstermek için kullanın. Seviye 1 metni piramit bölümlerinde, Seviye 2 metni ise her bölümün yanındaki şekillerde görünür. |
| LabeledHierarchy | `69` | Yukarıdan aşağıya ilerleyen ve hiyerarşik olarak gruplanmış ilişkileri göstermek için kullanın. Başlık veya seviye 1 metnini vurgular. Seviye 1 metninin ilk satırı hiyerarşinin başlangıcındaki şekilde görünür, sonraki tüm satırlar uzun dikdörtgenlerin solunda görülür. |
| LinearVenn | `70` | Sıra içinde üst üste binen ilişkileri göstermek için kullanın. Yalnızca Seviye 1 metniyle en iyi şekilde çalışır. |
| LinedList | `71` | Kategorilere ve alt kategorilere bölünmüş büyük miktarda metni göstermek için kullanın. Çok seviyeli metinle iyi çalışır. Aynı seviyedeki metinler çizgilerle ayrılır. |
| MultidirectionalCycle | `72` | Her yönde gerçekleşebilen aşamaların, görevlerin veya olayların sürekli bir sırasını temsil etmek için kullanın. |
| NameandTitleOrganizationChart | `73` | Bir organizasyonda hiyerarşik bilgi veya raporlama ilişkilerini göstermek için kullanın. Başlık kutusuna metin girmek için doğrudan daha küçük dikdörtgen şekle yazın. Bu düzenle assistant shape ve Org Chart hanging layouts mevcuttur. |
| NestedTarget | `74` | Kapsama ilişkilerini göstermek için kullanın. Seviye 1 metninin ilk üç satırı şekillerin sol üst metnine karşılık gelir, Seviye 2 metni ise daha küçük şekillere karşılık gelir. Az sayıda Seviye 2 satırıyla en iyi şekilde çalışır. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde hâlâ kullanılabilir. |
| NondirectionalCycle | `75` | Dönerek devam eden aşamaların, görevlerin veya olayların sırasını temsil etmek için kullanın. Her şeklin aynı öneme sahiptir. Yönün belirtilmesinin gerekmediği durumlarda iyidir. |
| OpposingArrows | `76` | İki zıt fikri veya merkezi bir noktadan ayrılan fikirleri göstermek için kullanın. Seviye 1 metninin ilk iki satırı bir oka karşılık gelir. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde hâlâ kullanılabilir. |
| OpposingIdeas | `77` | İki zıt veya karşıt fikri göstermek için kullanın. Bir veya iki Seviye 1 öğesi içerebilir. Her Seviye 1 metni birden çok alt seviyeye sahip olabilir. Büyük miktarda metinle iyi çalışır. |
| OrganizationChart | `78` | Bir organizasyonda hiyerarşik bilgi veya raporlama ilişkilerini göstermek için kullanın. Bu düzenle assistant shape ve Org Chart hanging layouts mevcuttur. |
| PhasedProcess | `79` | Bir sürecin üç aşamasını göstermek için kullanın. Üç Seviye 1 öğeyle sınırlıdır. İlk iki Seviye 1 öğe her biri dört Seviye 2 öğe içerebilir, üçüncü Seviye 1 öğe sınırsız sayıda Seviye 2 öğe içerebilir. Az miktarda metinle en iyi şekilde çalışır. |
| PictureAccentBlocks | `80` | Köşeden başlayan bloklarda bir grup resmi göstermek için kullanın. İlgili metin dikey olarak görüntülenir. Başlık veya alt başlık slaytlarında vurgu olarak veya bir belgenin bölüm ayrımlarında iyi çalışır. |
| PictureAccentList | `81` | Gruplandırılmış veya ilgili bilgiyi göstermek için kullanın. Üst köşelerdeki küçük şekiller resim içerecek şekilde tasarlanmıştır. Seviye 2 metnini Seviye 1 metnine göre vurgular ve büyük miktarda Seviye 2 metni için iyi bir seçimdir. |
| PictureAccentProcess | `82` | Bir görev, süreç veya iş akışındaki sıralı adımları göstermek için kullanın. Arka plandaki dikdörtgen şekiller resim içerecek şekilde tasarlanmıştır. |
| PictureCaptionList | `83` | Sırasız veya gruplandırılmış bilgi bloklarını göstermek için kullanın. Üst şekiller resim içerecek şekilde tasarlanmıştır ve resimler metne göre vurgulanır. Kısa metin başlıkları olan resimler için iyidir. |
| PictureGrid | `84` | Kare bir ızgara üzerine yerleştirilmiş resimleri göstermek için kullanın. Resmin üstünde görünen az miktarda Seviye 1 metinle en iyisidir. |
| PictureLineup | `85` | Yan yana bir dizi resmi göstermek için kullanın. Seviye 1 metni resmin üstünü kaplar. Seviye 2 metni resmin altında görünür. |
| PictureStrips | `86` | Üstten aşağıya bir dizi resmi ve yanlarındaki Seviye 1 metni göstermek için kullanın. |
| PieProcess | `87` | Bir süreçteki adımları, her bir dilimin boyutu yedi şekle kadar artacak şekilde göstermek için kullanın. Seviye 1 metni dikey olarak görüntülenir. |
| PlusandMinus | `88` | İki fikrin artılarını ve eksilerini göstermek için kullanın. Her Seviye 1 metni birden çok alt seviyeye sahip olabilir. Büyük miktarda metinle iyidir. İki Seviye 1 öğeyle sınırlıdır. |
| ProcessArrows | `89` | Bir süreç veya iş akışını gösteren bilgiyi göstermek için kullanın. Seviye 1 metni dairesel şekillerde, Seviye 2 metni ok şekillerinde görünür. Az metin ve hareket ya da yön vurgulanması gerektiğinde en iyisidir. |
| ProcessList | `90` | Bir görev, süreç veya iş akışındaki birden çok bilgi grubunu veya adım ve alt adımları göstermek için kullanın. Seviye 1 metni üst yatay şekillere karşılık gelir, Seviye 2 metni ise ilgili üst düzey şeklin altındaki dikey alt adımlara karşılık gelir. |
| PyramidList | `91` | Orantılı, birbirine bağlı veya hiyerarşik ilişkileri göstermek için kullanın. Metin piramit arka planının üzerindeki dikdörtgen şekillerde görünür. |
| RadialCluster | `92` | Merkez bir fikir veya temayla ilişkili verileri göstermek için kullanın. Üst Seviye 1 metni merkezde görünür. Seviye 2 metni çevredeki şekillerde görünür. En fazla yedi Seviye 2 şekil içerebilir. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde hâlâ kullanılabilir. Az miktarda metinle en iyisidir. |
| RadialCycle | `93` | Merkez bir fikre olan ilişkiyi göstermek için kullanın. Hem merkezdeki dairedeki bilgiyi hem de dış halkadaki dairelerdeki bilginin merkez fikre katkısını vurgular. Seviye 1 metninin ilk satırı merkez daireye, Seviye 2 metni dış halkadaki dairelere karşılık gelir. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde hâlâ kullanılabilir. |
| RadialList | `94` | Bir döngü içinde merkez bir fikre olan ilişkileri göstermek için kullanın. Merkez şekil bir resim içerebilir. Seviye 1 metni daha küçük dairelerde, ilgili Seviye 2 metni ise daha küçük dairelerin yanında görünür. |
| RadialVenn | `95` | Üst üste binen ilişkileri ve bir döngüdeki merkez fikre olan ilişkiyi göstermek için kullanın. Seviye 1 metninin ilk satırı merkez şekle, Seviye 2 metni ise çevredeki dairesel şekillere karşılık gelir. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde hâlâ kullanılabilir. |
| RandomToResultProcess | `96` | Bir dizi adım aracılığıyla, birkaç kaotik fikrin nasıl birleşik bir hedefe veya fikre dönüşebileceğini göstermek için kullanın. Birden çok Seviye 1 metni öğesini destekler, ancak ilk ve son Seviye 1 şekilleri sabittir. Az miktarda Seviye 1 metni ve orta miktarda Seviye 2 metniyle en iyisidir. |
| RepeatingBendingProcess | `97` | Bir görev, süreç veya iş akışındaki ilerlemeyi veya sıralı adımları göstermek için kullanın. Şekiller için hem yatay hem de dikey görüntü alanını en üst düzeye çıkarır. |
| ReverseList | `98` | İki öğe arasında geçiş yapmak için kullanın. Yalnızca ilk iki metin öğesi görüntülenir ve her öğe büyük miktarda metin içerebilir. İki öğe arasındaki değişikliği veya sıralamadaki kaymayı göstermek için iyidir. |
| SegmentedCycle | `99` | Döngüsel bir akışta aşamaların, görevlerin veya olayların ilerlemesini veya sırasını göstermek için kullanın. Birbirine bağlı parçaları vurgular. Seviye 1 metninin ilk yedi satırı bir dilim ya da pasta şekline karşılık gelir. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde hâlâ kullanılabilir. |
| SegmentedProcess | `100` | Bir görev, süreç veya iş akışındaki ilerlemeyi veya sıralı adımları göstermek için kullanın. Her satır ayrı bir şekilde göründüğü için Seviye 2 metnini vurgular. |
| SegmentedPyramid | `101` | Kapsama, orantılı veya birbirine bağlı ilişkileri göstermek için kullanın. Seviye 1 metninin ilk dokuz satırı üçgen şekillerde görünür. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde hâlâ kullanılabilir. Yalnızca Seviye 1 metniyle en iyisidir. |
| SnapshotPictureList | `102` | Açıklayıcı metinle birlikte resimleri göstermek için kullanın. Seviye 2 metni bilgi listeleri gösterebilir. Büyük miktarda metinle iyi çalışır. |
| SpiralPicture | `103` | Merkeze doğru spiral şeklinde dönen, karşılık gelen Seviye 1 altyazılı en fazla beş resmi göstermek için kullanın. |
| SquareAccentList | `104` | Kategorilere bölünmüş bilgi listelerini göstermek için kullanın. Seviye 2 metni küçük bir kare şeklin yanında görüntülenir. Büyük miktarda Seviye 2 metniyle iyi çalışır. |
| StackedList | `105` | Bir görev, süreç veya iş akışındaki bilgi gruplarını veya adımları göstermek için kullanın. Dairesel şekiller Seviye 1 metnini, ilgili dikdörtgenler ise Seviye 2 metnini içerir. Çok sayıda detay ve az Seviye 1 metni için iyi çalışır. |
| StackedVenn | `106` | Üst üste gelen ilişkileri göstermek için kullanılır. Büyümeyi veya derecelendirmeyi vurgulamak için iyi bir seçimdir. Yalnızca Seviye 1 metniyle en iyi çalışır. Seviye 1 metninin ilk yedi satırı dairesel bir şekle karşılık gelir. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde mevcut kalır. |
| StaggeredProcess | `107` | Aşamalar boyunca aşağı doğru bir ilerlemeyi göstermek için kullanılır. Seviye 1 metninin ilk beş satırı bir dikdörtgene karşılık gelir. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde mevcut kalır. |
| StepDownProcess | `108` | Birden fazla adım ve alt adımla aşağı doğru bir süreci göstermek için kullanılır. Az metinle en iyi çalışır. |
| StepUpProcess | `109` | Yukarı doğru bir adım serisini veya bilgi listelerini göstermek için kullanılır. |
| SubStepProcess | `110` | Seviye 1 metninin her örneği arasında alt adımlarla çok adımlı bir süreci göstermek için kullanılır. Az metinle en iyi çalışır ve yedi Seviye 1 adımı ile sınırlıdır. Her Seviye 1 adımı sınırsız sayıda alt adım içerebilir. |
| TableHierarchy | `111` | Üstten alta inen bilgi gruplarını ve her grup içindeki hiyerarşileri göstermek için kullanılır. Bu düzen bağlayıcı çizgiler içermez. |
| TableList | `112` | Eşit değerde gruplanmış veya ilgili bilgileri göstermek için kullanılır. Metnin ilk Seviye 1 satırı üst şekle karşılık gelir ve onun Seviye 2 metni sonraki listeler için kullanılır. |
| TargetList | `113` | İlişkili veya üst üste gelen bilgileri göstermek için kullanılır. Seviye 1 metninin ilk yedi satırı dikdörtgen şekil içinde görünür. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde mevcut kalır. Hem Seviye 1 hem de Seviye 2 metniyle iyi çalışır. |
| TextCycle | `114` | Aşamaların, görevlerin veya olayların sürekli bir dizisini dairesel bir akışta temsil etmek için kullanılır. Aşamalar veya adımlar yerine okları veya akışı vurgular. Yalnızca Seviye 1 metniyle en iyi çalışır. |
| TitlePictureLineup | `115` | Her biri kendi başlığı ve açıklaması olan bir dizi resmi göstermek için kullanılır. Seviye 1 metni resmin üzerindeki kutuda görünür. Seviye 2 metni resmin altında görünür. |
| TitledMatrix | `116` | Dört çeyrek ile bütün arasındaki ilişkileri göstermek için kullanılır. Seviye 1 metninin ilk satırı merkezi şekle karşılık gelir ve Seviye 2 metninin ilk dört satırı çeyreklerde görünür. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde mevcut kalır. |
| TitledPictureAccentList | `117` | Her Seviye 2 metni için bir vurgu resmi içeren bilgi listelerini göstermek için kullanılır. Seviye 1 metni listenin üst kısmında ayrı bir kutuda görüntülenir. |
| TitledPictureBlocks | `118` | Bir dizi resmi göstermek için kullanılır. Seviye 1 metni her resmin üzerinde görünür. Seviye 2 metni yan tarafta ve hafifçe resme üst üste gelecek şekilde görünür. |
| TrapezoidList | `119` | Eşit değerde gruplanmış veya ilgili bilgileri göstermek için kullanılır. Büyük miktarda metinle iyi çalışır. |
| UpwardArrow | `120` | Bir görev, süreç veya iş akışında yukarı doğru eğilim gösteren bir ilerleme veya adımları göstermek için kullanılır. Seviye 1 metninin ilk beş satırı ok üzerindeki bir noktaya karşılık gelir. Minimum metinle en iyi çalışır. Kullanılmayan metin görünmez, ancak düzenleri değiştirdiğinizde mevcut kalır. |
| VerticalAccentList | `121` | Bilgi listelerini göstermek için kullanılır. Seviye 2 metni dikey şeritlerin üzerindeki dikdörtgen şekillerde görünür. Seviye 2 metnini Seviye 1 metnine göre vurgular ve orta miktarda Seviye 2 metni için iyi bir seçimdir. |
| VerticalArrowList | `122` | Ortak bir hedefe doğru ilerleyen bir görev, süreç veya iş akışında bir ilerleme veya sıralı adımları göstermek için kullanılır. Madde işaretli bilgi listeleri için iyi çalışır. |
| VerticalBendingProcess | `123` | Bir görev, süreç veya iş akışında bir ilerleme veya sıralı adımları göstermek için kullanılır. Şekiller için yatay ve dikey görüntü alanını en üst düzeye çıkarır. Yön veya hareketten ziyade şekiller arasındaki karşılıklı ilişkileri vurgular. |
| VerticalBlockList | `124` | Bir görev, süreç veya iş akışında bilgi gruplarını veya adımları göstermek için kullanılır. Büyük miktarda Seviye 2 metniyle iyi çalışır. Ana noktası ve birden çok alt noktası olan metinler için iyi bir seçimdir. |
| VerticalBoxList | `125` | Özellikle büyük miktarda Seviye 2 metni içeren birkaç bilgi grubunu göstermek için kullanılır. Madde işaretli bilgi listeleri için iyi bir seçimdir. |
| VerticalBulletList | `126` | Sırasız veya gruplanmış bilgi bloklarını göstermek için kullanılır. Uzun başlıklar veya üst seviye bilgiler içeren listeler için iyi çalışır. |
| VerticalChevronList | `127` | Bir görev, süreç veya iş akışında bir ilerleme veya sıralı adımları göstermek veya hareketi/yönü vurgulamak için kullanılır. Seviye 2 metnini Seviye 1 metnine göre vurgular ve büyük miktarda Seviye 2 metni için iyi bir seçimdir. |
| VerticalCircleList | `128` | Sıralı veya gruplanmış verileri göstermek için kullanılır. Büyük dairesel bir şeklin yanında görüntülenen Seviye 1 metniyle en iyi çalışır. Alt seviyeler daha küçük dairesel şekillerle ayrılır. |
| VerticalCurvedList | `129` | Bilgi listesini kavisli bir şekilde göstermek için kullanılır. Vurgu daire şekillerine resim eklemek için resim doldurması uygulayın. |
| VerticalEquation | `130` | Bir planı veya sonucu gösteren sıralı adımları veya görevleri göstermek için kullanılır. Metnin son Seviye 1 satırı ok sonrasında görünür. Yalnızca Seviye 1 metniyle en iyi çalışır. |
| VerticalPictureAccentList | `131` | Sırasız veya gruplanmış bilgi bloklarını göstermek için kullanılır. Küçük daireler resim barındırmak için tasarlanmıştır. |
| VerticalPictureList | `132` | Sırasız veya gruplanmış bilgi bloklarını göstermek için kullanılır. Soldaki küçük şekiller resim barındırmak için tasarlanmıştır. |
| VerticalProcess | `133` | Bir görev, süreç veya iş akışında üstten aşağıya doğru bir ilerleme veya sıralı adımları göstermek için kullanılır. Dikey alan sınırlı olduğundan yalnızca Seviye 1 metniyle en iyi çalışır. |
| Custom | `134` | Özel düzen şablonlu bir SmartArt diyagramını temsil eder |
| PictureOrganizationChart | `135` | Bir organizasyonda hiyerarşik bilgiler veya raporlama ilişkilerini, ilgili resimlerle göstermek için kullanılır. Bu düzenle asistan şekli ve Org Chart asılı düzenleri mevcuttur. |

### Ayrıca Bakınız

* ad alanı [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->