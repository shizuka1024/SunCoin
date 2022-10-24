## 壹、摘要

　　本研究主旨是建立一個SunCoin區塊鏈系統，作為太陽能與電動車之間的橋樑，協助電力開發商籌措發展太陽能的資金，也作為電動車(消費者)充電的給付工具，利用區塊鏈有效管理能源利用，建立期權交易制度並建立信用評級制度，管控風險並維護SunCoin的價值和有效運作。

　　近年來隨著環保意識的抬頭，綠能的發展愈來愈受到重視，而太陽能不受開採、運輸的限制，成為綠能中有極大發展潛力的一種替代方案，如果太陽能可以結合電動車，將可以大大有助於環境保護，並解決部分的能源問題。

　　在太陽能與電動車的使用者之間會有一定的結合問題，在這個金融創新的企劃案中，我們建議使用區塊鏈把它們「鏈」在一起，使它們發揮最大效益，倘若我們提出的方案能夠實現，既可以將太陽能做有效的利用，節省不必要的能源浪費，又可以透過區塊鏈連結電力開發(投資者)、電力供應商及電力消費者(電動車)三者之間的關係，讓整體系統發揮最大的效益。

**關鍵字** ：區塊鏈(blockchain)、太陽能、電動車、智能合約

## 貳、研究動機與研究問題

　　鑒於區塊鏈世代演進，已經到了「物聯網智慧應用時代」，不只是人(自然人或法人)，而是每一個「物件」都將有一個帳戶，且各個帳戶之間可以直接互相溝通，以建構「第三代IOTA的智慧社會」。IOTA適用於物聯網及微型支付，其技術可解決比特幣、以太坊等現有區塊鏈因共識認證複雜，出現交易緩慢、難以普遍化、規模化的問題。IOTA透過較為簡單的演算法，讓每個鏈上的交易者都可以參與加密，且不需全體認證，透過智能合約，縮短加密時間。

　　雖然以太陽能電力支援電能車的電力消費是一個可行的方案，但仍有幾個問題待解決，例如：

1. 投入太陽能電力生產需要大量資金；
2. 電力供應商之間電力調度問題；
3. 電動車充電問題: 由於電池容量的問題，電動車可能經常需要充電，這就需要一個系統支援小額的、例常性的給付；我們的解決方案就是利用第三代IOTA區塊鏈系統SunCoin。要讓電動車普及，充電樁也應能支援簡單的付款方式。

　　在我們的應用場景裡，透過區塊鏈連結同一社區住戶的太陽能板、電網、儲能設備及電樁。利用自家電動車的充電樁時，可以透過區塊鏈智慧合約實現能源共享。在電動車充電時，電動車、充電站可以自行驗證身分。在第三代區塊鏈網絡中，電動車和充電樁都有自己的錢包(Wallet)，並且電動車可以使用自身帳戶的金錢自動付錢給充電站，交易的紀錄自動寫入區塊鏈中，不再需設專人收銀，既解決公共充電樁過少的問題，又能貼補家用，經濟又實惠！


![i1](https://user-images.githubusercontent.com/56194005/197532615-34a068fd-3c44-40e1-98c1-32880f7d77fc.png)

【圖1】以區塊鏈連結電網、充電樁、電動車示意

## 參、文獻回顧與探討

### 3.1 綠電的發展與重要性

　　近年來綠能備受重視，世界各國紛紛投身技術研發，瑞典、挪威、葡萄牙、不丹等國都成功發展綠能發電，打造環保家園。近年來臺灣再生能源佔總發電量的比例也逐年上升，在「前瞻基礎建設計畫」中的綠能建設部分中更是提到，政府在106-110年內分3期投入總數為207.85億元的特別預算[1]。綠能發電中，太陽能發電是一種利用光電效應把陽光轉換成電流的發電方式，適合在像台灣這樣日照很長的國家中推展。

　　除了建置太陽能發電廠外，太陽能發電也被廣泛建設於建築外牆、都市、甚至是自家屋頂，發展小型的、社區型的太陽能發電系統是具有很大可能性。臺灣從2000年開始推動太陽能發電，政府制訂了電力收購制度，使太陽能光電的發電量不斷增加，佔臺灣可再生能源發電量的23.3%。當然，太陽能發電站的建置成本是龐大的，資金需求是可觀的，社區型的、小型的民間太陽能發電設施是可行的、有效率的解決方案，但是不論電廠大小，資金籌措都是首要解決的問題。在2019年之前民間電廠只能售電給台電公司，在《再生能源發展條例》修正後，開放民間電廠可經由綠電直供（民間電廠直接供電給用戶）、綠電轉供（民間電廠經台電輸配電再供電給用戶）兩種經營型態販售綠電。但綠電交易模式新穎、電力轉供程序複雜，扮演媒合賣買方的「綠電中盤商」角色應運而生，迄今已有多家再生能源售電業誕生，包括陽光伏特家、台汽電綠能等都準備投入綠電交易市場。

　　綠電中盤商透過向上游再生能源發電廠買電，再轉賣給有綠電需求的用戶，從中賺取價差獲利，或提供加值的能源技術服務，如節能、儲能等，優化企業的用電效率。綠電交易市場看似「拉力」、「推力」俱足，但要能真正活絡起來，供需兩端還是面臨量能、價格、資金三大考驗；而需求端的重要來源之一就是強力崛起中的電動車。

### 3.2 電動車的發展

　　綠色消費概念已經逐漸受到全球性的重視；例如歐盟指引方針建議，從2021年開始，所有新登記車輛的二氧化碳排放量，需低於95克/公里。隨著環保意識的高漲，各國訂出明確禁售燃油車的時間，例如挪威、荷蘭都預計在2025年全面禁售燃油車；英國則打算在2040年前禁售燃油車；中國則要求，車廠必須生產一定比例的新能源車；日本經濟產業省也提出「2050年新乘用車全面電動化」的目標；我國政府也有訂出電動車的發展目標：「2040年新售汽車全面電動化」。

在新碳排放量規範上路後，全球預計五成的車廠可能面臨懲罰性罰鍰，估計全球汽車產業在2020至2021年將損失超過390億美金。不過正是因為高額罰款、品牌形象等壓力，促使傳統車廠加速汽車電動化轉型，電動車是所有主流車廠一致性的轉型目標，2020年全球有超過20家車廠有電動車上市規畫。

電動車若要普及，商用車市場扮演關鍵角色，DeloitteGlobal預測，2021年全西歐地區的汽車銷售總數中，企業採購比例將占63%，預估全球電動車未來十年的複合年成長率將達到29%，電動汽車的總銷量將從2020年的250萬輛，增長到3,110萬輛。面對這麼強勁的發展趨勢，電力的供應是必須解決的問題，方案之一就是充分利用太陽能電力。

　　在有效率的市場經濟中，供應端與需求端之間的距離越小越好，亦即中介層級越少越好，能源供應也不例外，我們要儘量「去中介化」(De-intermediarization) ，讓能源的供需，儘量跨越中間的中盤商，達成較有效率的綠電直供。這一點我們可以借助區塊鏈技術。

### 3.3 區塊的興起與運用廣泛

　　自從2008年中本聰發表了比特幣白皮書以後，區塊鏈技術及其應用就得到廣泛重視；區塊鏈的特色包括：

1. 去中心化/去中介化: 這個特性可以降低交易成本。
2. 分散式處理與儲存，強化資訊安全。
3. 資料難以竄改性，強化系統的信任。
4. 使用公共帳本，交易透明。

區塊鏈發展至今，已經經歷了三個世代，但三個世代的區塊鏈系統卻並行蓬勃的發展著:

第一代以比特幣為代表，主要發展了加密貨幣；

第二代以乙太坊為代表，主要發展了智能合約；

第三代為智慧型應用，隨著物聯網(Internet of Things, IoT)基礎設施不斷擴展，企業自然而然地也開始加以利用，智慧型系統提供的服務越來越多，其中可用於收費的服務也逐漸增多。在這個發展過程中，人們期望可以使用合適的電子貨幣支付小額費用和小額購買，即進行小額支付，於是便出現了IOTA，這是一種基於「分類帳」(ledger)的技術，專為IoT而設計，可用於實現小額的、例常性的、高頻率的支付。在這個智慧應用系統中，除了自然人、法人之外，參與運作的實體如電動車、充電樁等也會有獨立的帳戶，在其所有人的授權下，依照智慧合約獨立運作。

電子支付系統必須在安全性、個性化和便利性方面做得更優越。而IOTA恰恰在這些方面具備優勢，相較於其它電子支付方式，它有三項主要的優勢：模組化、去中心化且低交易成本。IOTA基於一種名為Tangle的新型分散式分類帳，克服了當前區塊鏈設計的低效率，在去中心化的點對點解決方案中導入了一種新的共識方法。例如，這種方法允許使用該技術進行支付生活開支的各種轉帳，而無需支付任何手續費，例如停車費、洗車費或甚至是電動車充電，我們的Suncoin區塊鏈系統設計就是站在第三代區塊鏈系統的基礎出發的。

　　面對《再生能源發展條例》修正後，社區自我供電用的太陽能將不再因生產過剩而浪費，透過我們的SunCoin平台，將過剩的供電販售給電動車，社區能夠自給自足且對外販售，也彌補電動車充電樁數量不足且散佈不均等缺陷，達到雙贏局面。

## 肆、研究方法及步驟

### 4.1 SunCoin區塊鏈系統的設計

　　SunCoin是一個第三代區塊鏈系統，它的主要功能為：

  1. 仿效比特幣或乙太坊，發行有限數量的加密貨幣SunCoin(例如十億枚1 Billion)。正如Bitcoin一樣，SunCoin既是一個系統，也是一種加密貨幣。SunCoin虛擬貨幣將用支援太陽能電力生產、交換和消費之用。所有的SunCoin並非一次全數釋出，而是像比特幣等依照一定規則逐步釋出。在此一系統中， SunCoin作為交易工具。
  2. SunCoin區塊鏈將處理及紀錄所有的交易，以確立系統的可信賴性，投資、電力調度、電動車充電等作業，不論金額大小，都會翔實記錄在區塊鏈裡，確保系統的可靠性。。
  3. 綠能電廠、綠能企業可以作ICO募資，透過購買或是生產設備建置可以讓SunCoin具有基本價值，並使其成為綠能消費的給付工具以及電力調度的清算工具。
  4. 社區的綠電能不足，需要向其他綠能電廠/社區進行電力調度，也可以透過SunCoin完成付款；反之若該社區有多餘綠電，亦可售出給予其他缺乏電力的社區或個別用戶。

### 4.2 利用ICO為太陽能募資

　　不管是大型太陽能電廠或是小型社區發電站，建置費用是一筆可觀的資金，因此，一個可行的方案必須能協助解決資金需求問題，同時也要為產量尋找需求者。在此，我們提出SunCoin的「首次貨幣發行(Initial Coin Offering, ICO」募資。募資的對象可以是殷實的投資者，也可以是一般社會大眾，也就是群眾募資(Crowd Fuding)。殷實的投資者可以因投資而獲利達到資本利得，而一般社會大眾則可以購買能源幣來為他們的電動車充電；而電動車充電可以為太陽能產業提供強而有力的需求，促進綠能的發展。

### 4.3 SunCoin支援綠電供應商之間的電力調度

　　太陽能供電會隨天氣陰晴而變化，不是特別穩定，將來各個電力商之間可能必須互相支援以調度電力，SunCoin則可以做為它們之間的清算工具。更進一步考慮，各社區、各汽車對電力的需求也不是恆定不變，因此智慧的電網和有效率的電力調度是至關重要的。SunCoin區塊鏈將累積大量電力商和用戶的使用數據，提供大數據分析的基礎，使電力供應儘量智慧化。

### 4.4 電動車充電消費的交易

　　人們的電動車停在充電樁時，透過智慧合約(Smart Contract)，電動車可自動與充電樁溝通，並使用 SunCoin 完成付款，整個交易均會紀錄於SunCoin系統中。SunCoin系統更可將使用者、綠能電廠、充電站之間的交易資料，全部串於SunCoin區塊鏈中，大幅提升交易安全性。若任何一個環節有問題，均可透過SunCoin系統中的區塊鏈資料進行溯源。社區住戶若想知道自己社區的的電力供應及使用情形，在得到授權之後，可以在公共帳本查找，資訊透明且正確。

![i2](https://user-images.githubusercontent.com/56194005/197532785-e90d244c-1e00-4f49-8192-98fe1d40ed8a.png)

【圖4】電動車與充電樁運作模式

### 4.5 SunCoin系統的創新性

本系統的創新在於具有未來性及前瞻性，具體說明如下：

- 我們利用能源幣SunCoin支援綠能產業及電動車的發展，而太陽能及電動車則是國家未來產業發展的重點。新興產業的發展需要資金、需要使用者(市場)，SunCoin都可以提供部分解決方案。
- 利用區塊鏈有效管理能源利用。由於太陽能發電與天候息息相關，而社區(或電動車)對電力的需求也不是固定的，因此藉由SunCoin可以支援電力商之間電力調度的清算，藉由區塊鏈資料提供大數據分析，可以較準確的掌握能源的供需狀況。
- SunCoin的價值維護和有效運作也是重要的創新。一種資產唯有透過交易，才能維護它的價值。我們將建立期權交易制度，促進SunCoin流通。

## 伍、預期結果

　　我們從環保的角度出發，著眼下一階段的重點產業「綠能與電動車」利用新發展的資訊技術區塊鏈將他們連結起來，作為金融服務的創新。在此我們建立一個SunCoin區塊鏈系統，透過「首次貨幣發行(ICO)」募資，協助電力開發商籌措發展太陽能的資金，也作為電動車(消費者)充電的給付工具。同時，它也可以作為電力供應商之間電力調度的支付計量基準。

　　由於SunCoin的總量是有上限的，因此其價值是有保障的，並且其價格取決於供需法則。為了促進SunCoin的流通，並促使太陽能支援電動車的發展，我們建置了SunCoin的交易平台，建立期權交易制度，有效管理能源的供需及維護SunCoin的合理幣值。本企劃案若能實現，既可以將太陽能作有效的利用，節省不必要的能源浪費，又可以透過區塊鏈連結電力開發(投資者)、電力供應商及電力消費者(電動車)三者之間的關係，讓整體系統發揮最大的效益，創造未來性及創新性。

## 陸、參考文獻

[1]Satoshi Nakamoto，"Bitcoin: A Peer-to-Peer Electronic Cash System"

[https://bitcoin.org/bitcoin.pdf](https://bitcoin.org/bitcoin.pdf)

[2]前瞻基礎建設特別條例

[https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=A0030293](https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=A0030293)

[3]高敬原，電動車靠這4大關鍵崛起，10年後將突破3千萬輛！一張圖看懂未來趨勢，2020年9月28日報導

[https://www.bnext.com.tw/article/59412/2030-electricvehicle-trends](https://www.bnext.com.tw/article/59412/2030-electricvehicle-trends)

[4]《Electric vehicles．Setting a course for 2030》

[https://www2.deloitte.com/uk/en/insights/focus/future-of-mobility/electric-vehicle-trends-2030.html](https://www2.deloitte.com/uk/en/insights/focus/future-of-mobility/electric-vehicle-trends-2030.html)

[5]陳聖豪、陳榮傑，"乙太坊與其共識演算法Casper"

[https://hdl.handle.net/11296/5ve2e5](https://hdl.handle.net/11296/5ve2e5)

[6]Shyan-Ming Yuan，"Elastic and Cost-effective Data Carrier Architecture for Ethereum Smart Contract,"

[https://hdl.handle.net/11296/zjx6pw](https://hdl.handle.net/11296/zjx6pw)

[7]徐粲翔，"Gcoin 智能合約架構"

[https://hdl.handle.net/11296/3m2b4q](https://hdl.handle.net/11296/3m2b4q)

[8]邱喜文，"AIoT技術應用於能源管理之個案研究"

[https://hdl.handle.net/11296/7jd4ms](https://hdl.handle.net/11296/7jd4ms)

[9]Victor Daniel Maldonado Garibay，"Artificial Intelligence and Blockchain Technologies in Managing Money Laundering Risk"

[https://hdl.handle.net/11296/a9329d](https://hdl.handle.net/11296/a9329d)

[10]陳盈鈞，"應用區塊鍊共識機制執行任務量證明之高安全性霧運算平台"

[https://hdl.handle.net/11296/5637mq](https://hdl.handle.net/11296/5637mq)

[11]颜拥、赵俊华、文福拴、陈星莺，"能源系统中的区块链:概念、应用与展望"

[https://www.cnki.com.cn/Article/CJFDTotal-DLJS201702002.htm](https://www.cnki.com.cn/Article/CJFDTotal-DLJS201702002.htm)

[12]Chun-Wei Chang，"Governance structure for virtual asset issuance and management on bitcoin-like Blockchain, "

[https://hdl.handle.net/11296/wp9k56](https://hdl.handle.net/11296/wp9k56)

[13]Yuan Yong、Wang Fei-Yue，"Blockchain: The State of the Art and Future Trends, "

[http://html.rhhz.net/ZDHXBZWB/html/20160401.htm](http://html.rhhz.net/ZDHXBZWB/html/20160401.htm)

[14]Zhang Ning、 Wang Yi、 Kang Chongqing、 Cheng Jiangnan、He Dawei，"Blockchain Technique in the Energy Internet:Preliminary Research Framework and Typical Applications, "

[https://www.researchgate.net/publication/305640411\_nengyuanhulianwangzhongdequkuailianjishuyanjiukuangjiayudianxingyingyongchutanBlockchain\_Technique\_in\_the\_Energy\_Internet\_Preliminary\_Research\_Framework\_and\_Typical\_Applications](https://www.researchgate.net/publication/305640411_nengyuanhulianwangzhongdequkuailianjishuyanjiukuangjiayudianxingyingyongchutanBlockchain_Technique_in_the_Energy_Internet_Preliminary_Research_Framework_and_Typical_Applications)

[15]仲盛、黄欣沂，"区块链应用中的安全隐私专题简介"

[http://scis.scichina.com/cn/2020/SSI-2020-0031.pdf](http://scis.scichina.com/cn/2020/SSI-2020-0031.pdf)

## 柒、需要指導教授指導內容

　　本研究主旨是建立一個區塊鏈系統，為了托善的將太陽能與電動車「鏈」在一起，我們嘗試結合「第三代IOTA的智慧社會」技術，藉以打造一個有效的解決方案。

　　指導教授陳志誠教授為電子金融與金融資訊系統安全體系出身，且專長為區塊鏈，近期更甚至獲得「區塊鏈會計」的專利，我們認為許多有關於區塊鏈知識、清算與交易給付服務情境還有期權交易制度都是我們在提出SunCoin平台所欠缺的能力，此研究是我們的構想，在許多細節與內容上可能考慮未必周詳，亟需指導教授針對幾個方向為我們指導：

一、研究架構完整性：針對此研究的架構是否完整及後續細節建立進行指導及修

正。

二、首次貨幣發行(ICO)：在區塊鏈眾籌，用區塊鏈把使用權和加密貨幣合一，在

項目進行融資的方式還需要詳細的指導。

三、研究貨幣供需法則：由於SunCoin的總量是有上限的，因此其價值是有保障的

，並且其價格取決於供需法則，有效預測能源的供需，提升市場的效率，使得

綠能產業健全發展。

四、研究未來方向指正：對於研究之未來可能發展，由於學生的研究經驗不足，指

導教授可適時指引我們未來可能發展方向。
