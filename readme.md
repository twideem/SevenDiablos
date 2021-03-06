# Seven Diablos

什麼都靠打怪掉落，但怎麼打就是打不到。能不能只要努力農材料、打怪賺錢，就換獨特裝備穿？

本修改的設計是，用普通難度就能農到的材料，來合成各式裝備的赫拉迪克方塊公式，但又不至於三兩下就全身獨特裝備或成套裝備，享受有個目標可以追逐、稍加努力便能實現的樂趣～

為了農材料重複刷同樣關卡很乏味，覺得通關過程努力打怪賺錢就可買獨特裝備穿的話，也可向 NPC 購買材料來合成。

過去，你每次重玩《暗黑破壞神 II》，大概只會練兩個最拿手的流派，就玩完收手了。現在，你會大呼過癮的把七種職業都練一次才收手（所以取名 Seven Diablos），因為修改過後玩起來就是痛快！

## 下載與使用

* 需求

  適用《暗黑破壞神 II：毀滅之王》1.13c 版和 1.14d 版，且創造新人物時必須勾選「資料片人物」，否則會當機。

* 下載

  請按 Code，再按 Download ZIP。

* 安裝與移除

  解開壓縮檔後，將 data 資料夾放在 Diablo II 資料夾，然後以 Diablo II.exe -direct -txt 啟動遊戲。

  不再使用這個的話，將 data 資料夾刪除即可。

* 聲明

  只要你有在玩 BATTLE.NET，就不要下載使用這個單機修改，否則帳號會被封鎖！

  雖然玩 BATTLE.NET 時，不要下 -direct -txt 參數就沒事，但事實證明你總會忘記，不小心在 -direct -txt 參數模式下以修改過的設定玩 BATTLE.NET！

  所以本單機修改僅限只玩單機沒在玩 BATTLE.NET 的人使用！

## 修改項目

* 角色修改

  * 跑步時不消耗耐力。
  * 一開始就有赫拉迪克方塊。覺得會影響劇情發展的話，可以丟到地上。

  不喜歡這些修改的話，可將 charstats.txt 刪除，不會影響其它單機修改部分。

* 怪物修改

  * 取消稀有 BOSS 的燃燒法力屬性。隨劇情任務固定出現的 BOSS，屬性是寫死的，並不是隨機產生屬性的稀有 BOSS，所以依然有燃燒法力，例如 ACT 5 解救安亞時遇到的冰凍怪魔。

  不喜歡這項修改的話，可將 monumod.txt 刪除，不會影響其它單機修改部分。

* 商店修改

  * ACT.1 阿卡拉賣赦免勳章，基德賣製作毒弓要用到的碎裂的綠寶石。
  * ACT.2 卓格南賣綠寶石以外的碎裂的其它寶石，雷山德賣回復活力葯劑。
  * ACT.3 奧瑪斯賣碎裂的骷髏，艾柯賣魔法詞綴寶石。
  * ACT.4 賈梅拉賣符文石和全面回復活力葯劑，好好對決暗黑破壞神吧！
  * ACT.5 安亞賣無瑕疵的寶石和骷髏。為什麼不賣完美的？因為合成符文石需要用到無瑕疵的，想要完美的，買三顆無瑕疵的合成就是了。

  售價為遊戲預先的設定，並未更動。

  提升難度時，NPC 賣的最低階葯劑會升階，例如輕微治療葯劑變成輕型治療葯劑，導致最後 NPC 賣的整排葯劑其實都是同一種，所以改為 NPC 只賣一種治療葯劑和法力葯劑，越高章節賣的越高階。

  可以用合成公式轉換成套裝備和獨特裝備的符文石，是故意擺在 ACT.4 才賣。因為普通難度在對決暗黑破壞神之前，全身爛裝也能通關，只有這章沒準備好會卡關，所以這時擺上符文石方便合成獨特裝備。先好好享受打藍裝穿或洗黃裝穿的樂趣，等到正式對決暗黑破壞神時，更能感受改穿獨特裝備的尊榮。

* 物品修改

  * 開啟天梯限定的符文組和獨特裝備。
  * 同件獨特裝備可重複出現，而不是每場遊戲只出現一次。
  * 獨特裝備、成套裝備、超強裝備，屬性效果都是最大值，不再浮動。
  * 裝甲的防禦都是最大值，不再浮動。
  * 鑰匙、城鎮傳送之書、辨視之書的數量上限為 100。

* 文字修改

  * 修正簡體字造成的亂碼。
  * 以．符號取代‧符號解決顯示為?的問題。
  * 符文石名稱後以圓弧顯示編號。
  * 將中文版翻譯錯誤的「增加準確率」和「準確率」，分別改為「提升攻擊速度」和「攻擊速度」。
  * 「攻擊時有 n% 機會施展等級 n 技能」前面加上「被」。
  * 修正德魯依技能說明的錯別字。
  * 修改雇傭兵的名字：喬安妮→喬安尼、奧蕾那→奧雷納、猶瑟r→猶瑟。

  不喜歡這些修改的話，可將 local 資料夾刪除，不會影響其它單機修改部分。

## 赫拉迪克方塊公式

行末有※符號的話，表示會有進一步的說明。

* 符文石

  * 裝備 + 艾爾(1)x3 = 正常裝備 ※
  * 裝備 + 艾德(2)x3 = 有凹槽 (2)
  * 裝備 + 特爾(3)x3 = 有凹槽 (3) 或上限
  * 裝備 + 那夫(4)x3 = 有凹槽 (4) 或上限
  * 裝備 + 愛斯(5)x3 = 有凹槽 (5) 或上限
  * 裝備 + 伊司(6)x3 = 有凹槽 (6) 或上限
  * 裝備 + 塔爾(7)x3 = 成套裝備
  * 物品 + 拉爾(8)x3 = 獨特物品 ※
  * 裝備 + 歐特(9)x3 = 提昇裝備等級為進階或菁英
  * 稀有物品 = 伊司(6) ※
  * 符文石 = 降低一階的符文石。

* 葯劑、寶石

  * 附魔裝備或稀有裝備 + 任意法力葯劑x3 = 重洗屬性 ※
  * 武器 + 任意治療葯劑x3 = 修復耐久度或補滿數量 ※
  * 有鑲嵌物的裝備 + 融解葯劑x3 = 清除鑲嵌物
  * 薩德x2 + 無瑕疵的鑽石 = 喬丹之石
  * 合成裝備（橘裝）的寶石改為顏色相符的寶石即可，不需要完美的。

* 雜項

  * 成套或獨特飾品 = 另一件成套或獨特飾品 ※

* 過渡裝

  * 物品 + 輕微治療葯劑 + 輕微法力葯劑 + 回復活力藥劑 = 過渡物品

    轉為過渡的物品，會附上基本屬性效果如下：

    1. 武器　　+80% 增強傷害、+3 所有技能、有凹槽 (2~6)
    2. 裝甲　　+65% 防禦強化、有凹槽 (2~6)
    3. 項鍊　　12% 受損的生命移至法力
    4. 戒指　　5% 額外的攻擊準確率加成
    5. 護符　　+5 照亮範圍

    其實這是遊戲未開放且沒什麼作用的「暗綠裝備」，本公式賦予「能夠疊加屬性效果上去」的功能，在沒有成套裝備、獨特武器前，作為湊著用的過渡裝備，效果如下：

    * 過渡武器 + 任意紅寶石x3 = 附加「增加 3-4 火焰傷害」屬性效果
    * 過渡武器 + 任意藍寶石x3 = 附加「增加 1-3 冰冷傷害」屬性效果
    * 過渡武器 + 任意黃寶石x3 = 附加「增加 1-8 閃電傷害」屬性效果
    * 過渡武器 + 任意綠寶石x3 = 附加「增加 10 毒素傷害，持續時間 3 秒」屬性效果
    * 過渡武器 + 任意骷髏x3 = 附加「2% 擊中偷取生命 1% 擊中偷取法力」屬性效果
    * 過渡盾牌 + 任意紫寶石x3 = 附加「+8 防禦」屬性效果
    * 過渡頭盔 + 辨視卷軸x3 = 附加「+20 準確率」屬性效果
    * 過渡衣甲 + 箭矢 = 附加「攻擊者受到傷害 4」屬性效果
    * 過渡腰帶 + 城鎮傳送卷軸x3 = 附加「生命補滿 +2 法力重生 8%」屬性效果
    * 過渡手套 + 十字弓彈 = 附加「增加 1-2 傷害」屬性效果
    * 過渡鞋子 + 體力葯劑x3 = 附加「10% 高速跑步行走」屬性效果
    * 過渡項鍊 + 任意鑽石x3 = 附加「+1 所有技能」屬性效果
    * 過渡戒指 + 解毒葯劑x3 = 附加「所有抗性 +6」屬性效果
    * 過渡小護身符 + 鑰匙 = 附加「+9% 更佳的機會取得魔法裝備」屬性效果

  過渡裝備純粹作為普通難度剛通關時湊著用。你應該把樂趣放在農足夠的符文石轉換成套裝備或獨特裝備來穿，而不是努力買材料合成出數值達上限的過渡裝備來用。也因此，你可以發現材料是普通難度才買得到的葯劑，一進入惡夢難度就沒辦法將物品轉為過渡裝備了～

* 作弊公式

  * 物品 + 辨視卷軸 = 作弊屬性效果的物品

    各物品的作弊屬性效果如下：

    * 武器、箭矢、十字弓彈

       武器會附加「等級 25 信念靈氣賦予」「等級 60 降低抵抗 (82 聚氣)」「打擊時有 100% 機會施展等級 1 衰老」屬性效果，給不喜歡火焰系無效、冰冷系無效、閃電系無效、毒素系無效、實體攻擊無效的人使用。

       但有五種情況無法破抗：

       1. 抗性超過 100% 時，降抗效果只有 1/5。而「信念」最高降抗 150%，「降低抵抗」最高降抗 70%，兩者一起使用可降抗 44%，因此怪物的抗性 145% 便註定無法破抗。（地獄難度下，沒有小怪電抗超過 140%，火抗 140% 以上的小怪只有一種，冰抗 140% 以上的小怪則有 49 種。知道為何電系最多人練，為何冰系要雙修的原因了吧？）
       2. 信念無法破除毒系傷害無效，只降其它三抗。
       3. 遊戲還有一種叫魔法抗性，也就是一次提升所有元素抗性，信念並不降低這種抗性。
       4. 信念降物理防禦的幅度其實不高，可能無法破實體攻擊無效。
       5. 隨劇情任務固定出現的 BOSS，屬性是另外寫死的，並不是隨機產生，這也無法破除。

       原則上只求能破除小怪的元素無效，把小怪清完再專心對付 BOSS。

       同一件物品，無法同時作用兩種靈氣，所以武器已有靈氣的話，會被作弊的靈氣取代。

       箭矢會附加「穿刺攻擊」與「擊退」屬性效果，機率是 100%。

       十字弓彈會附加「箭矢或十字弓彈火焰爆炸」屬性效果，範圍 13。

    * 防具

       裝甲、盾牌、頭盔會附加「+450 生命」「+5 生命（以角色等級決定）」「增加生命上限 50%」「+95 體力」「+5 體力（以角色等級決定）」屬性效果，給不喜歡死亡、不想傭兵狂死的人使用。

       手套會附加「+5 力量（以角色等級決定）」屬性效果，給力量不足以穿好裝的人使用。

       腰帶會附加「等級 25 冥思靈氣賦予」屬性效果，給不喜歡出門要帶藍水的人使用。

       鞋子會附加「等級 7 傳送 (50 聚氣)」「等級 7 加速 (50 聚氣)」「無法冰凍」「冰凍時間減半」屬性效果。

    * 物品

       項鍊會附加「+1 所有技能」屬性效果。

       戒指會附加「+25 準確率（以角色等級決定）」屬性效果，給不喜歡頻頻打不中怪的人使用，相當於每次升級點滿敏捷。

       護身符會附加「+50% 轉為經驗值獲得」「155% 更佳的機會取得魔法裝備」「7% 更佳的機會取得魔法裝備（以角色等級決定）」「+8 照亮範圍」。

       寶石會附加「+1.25 抗性（以角色等級決定）」屬性效果，給不喜歡負抗的人使用。每級增加 1.25 抗性的話，Lv.64 進地獄為 80，剛好抗性 0。

  * 辨視卷軸 = 作弊屬性效果的小護身符

    剛創角想全程以經驗神殿狀態練等，並一路快樂刷寶的話，請直接拿身上的辨視卷軸轉換，可得「+50% 轉為經驗值獲得」「155% 更佳的機會取得魔法裝備」「7% 更佳的機會取得魔法裝備（以角色等級決定）」「+8 照亮範圍」的大護身符。

    頭上會出現經驗神殿的圖示，等於經驗加成效果常駐。

    雖然照亮範圍 +5 就達上限，但有些裝備會 -3 照亮範圍，所以 +8 還是有實用性的。

    想要錢的話，也可以轉換辨視卷軸來賣。

  不建議使用作弊公式，會剝奪遊戲該有的樂趣，因為這是用來破壞遊戲平衡的屬性效果！除非你覺得想作弊的效果很合理，才使用它，否則一股腦兒全用的話，會覺得失真不好玩。

## 新增符文組

* 武器 : 伊司(6) 安姆(11) 艾爾(1)

  * 等級 12 信念靈氣賦予
  * -28% 對敵人火焰系抗性
  * -60% 對敵人冰凍系抗性
  * -55% 對敵人雷電系抗性
  * 打擊時有 100% 機會施展等級 40 暴風雪
  * 打擊時有 100% 機會施展等級 44 連鎖閃電
  * 打擊時有 100% 機會施展等級 48 隕石

* 頭盔 : 特爾(3) 伊司(6)

  * 等級 17 冥思靈氣賦予
  * +33 法力
  * +0.625 法力（以角色等級決定）
  * +10 精力
  * +2 所有技能
  * 300% 額外金幣從怪物身上取得
  * 100% 更加的機會取得魔法裝備

這些是遊戲未開放的符石排列組合，所以效果是空的，相當可惜。於是我把「無限」和「眼光」的靈氣挑出來，再從其它符文組挑出有趣的效果湊在一起，放在未開放的符文組裡，在等級還不夠組那兩個靈氣的符文武器時用。

另外還有一個「那夫(4) 索爾(12) 伊斯特(24)」符文組，但適用的物品是頂多只有兩個凹槽的魔杖，根本不可能組出來 XDDD

## 進一步說明

* 用詞說明

  「物品」表示還包含護身符。

  「飾品」表示項鍊和戒指但不含護身符。

* 正常裝備

  這是將藍裝、黃裝、綠裝、金裝轉為白裝的公式，想製作符文組裝備時用得到。

  為何不打一洞？因為指定洞數是為了符文組，至少兩洞，平常根本用不到一洞的裝備。

* 獨特物品

  飛刀、標槍、職業專屬裝備、菁英裝備，只特定幾種有獨特裝備，所以要轉這些裝備前要先查詢，否則會變成稀有裝備。除此之外的基礎裝備與進階裝備，都有獨特裝備可以轉。

  小型護身符可以轉為毀滅，大型護身符可以轉為地獄火炬，超大型護身符可以轉為吉黑得的運氣。

* 稀有物品換符文石

  這公式相當於打到 3 個黃裝可以打洞，9 個可以合成綠裝，27 個可以合成金裝。

  我認為以這樣的難度獲得這些裝備，既不會太簡單、也不會太困難，是相當好玩的公式。

  不然一直退出遊戲刷女伯爵也挺無趣的，一路農怪農到底打黃裝比較暢快啊！

* 重洗屬性

  重洗成套裝備與獨特裝備，是為了洗出浮動屬性效果的最大值。但這部分，本單機修改已經最大值，所以沒必要洗成套裝備和獨特裝備，便只提供重洗附魔裝備和稀有裝備的公式。

* 為何只有武器能用治療葯劑修復

  修復耐久度或補滿數量只對武器有效是故意的，因為不希望 NPC 修復裝備變得沒意義。

  這個公式讓遊戲原本就有的修復武器公式變得沒意義，不過武器實在壞得很快，經常出門沒打多久就要回城修理，所以還是設計了這個公式，提升遊戲進行的流暢度。

* 另一件成套或獨特飾品

  太多成套與獨特飾品共用同樣基礎物品，不容易轉換出想要的款式，因此設計了公式，可以直接對單一件成套或獨特項鍊、戒指、珠寶進行轉換成另一件，直到想要的款式。

  少數獨特裝備也共用同一件菁英裝備，通常是兩個獨特裝備共用一件菁英裝備，多準備材料轉換幾次就能獲得想要的，所以並未為這兩三件獨特裝備多寫一個公式。

## 建議搭配 PlugY 獲得更好的遊戲體驗

* 下載

  https://github.com/ChaosMarc/PlugY

* 功能

  * 大空間倉庫、多頁倉庫、共用倉庫。（ActiveBigStash=1、ActiveMultiPageStash=1、ActiveSharedStash=1）
  * 顯示物品等級。（ActiveDisplayItemLevel=1）
  * 按 Alt 撤銷 1 點屬性。（ActiveStatsUnassignment=1）
  * 按 Shift 一次配 10 點屬性。（ActiveShiftClickLimit=1）
  * 顯示未加上裝備效果的屬性點數。（ActiveDisplayBaseStatsValue=1）
  * 像天梯一樣，每次進遊戲重置地圖。（AlwaysRegenMapInSP=1）
  * 像天梯一樣，將 Act V 的迪卡．凱恩移到傳送點附近。（MoveCainNearHarrogathWaypoint=1）
  * 防止進入 BATTLE.NET。（DisableBattleNet=1）
  * 每次進遊戲自動輸入 /players 8。（NBPlayersByDefault=8，要關閉的話設為 0）
  * 啟用 data 裡修改的資料。（Param=-direct -txt）

  以上項目可在 PlugY.ini 修改，若沒找到想要的項目，請自己加上去。

  當然 PlugY 不只這些功能，像是可以透過 StatPerLevelUp 和 SkillPerLevelUp 修改升級時獲得的屬性和技能點數，請上網搜尋更多，打造更豐富的遊戲體驗吧～