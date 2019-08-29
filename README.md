# ai100-3

homework for https://ai100-3.cupoy.com/

# 目前已完成進度:day2



notes:

https://ai.googleblog.com/
https://research.fb.com/blog/
https://machinelearning.apple.com/
https://www.jiqizhixin.com/
https://www.leiphone.com/category/ai

https://www.youtube.com/watch?v=CXgbekl66jc&feature=youtu.be
https://kopu.chat/2017/07/28/機器是怎麼從資料中「學」到東西的呢/  
https://www.ted.com/talks/fei_fei_li_how_we_re_teaching_computers_to_understand_pictures?language=zh-tw




steps:
1. 資料清整（Data Cleaning）:機器既然得從海量資料中挖掘出規律，「乾淨」的數據在分析時便非常地關鍵。在分析的一開始時，得處理資料的格式不一致、缺失值、無效值等異常狀況，並視資料分佈狀態，決定如何填入資料，或移除欄位，確保不把錯誤和偏差的資料帶入到資料分析的過程中去。
2. 特徵萃取 (Feature Extraction) 與特徵選擇 (Feature Selection): 特徵萃取 (Feature Extraction) 是從資料中挖出可以用的特徵，比如每個會員的性別、年齡、消費金額等；再把特徵量化、如性別可以變成 0 或 1 ，如此以來每個會員都可以變成一個多維度的向量。經過特整萃取後，特徵選擇 (Feature Selection) 根據機器學習模型學習的結果，去看什麼樣的特稱是比較重要的。若是要分析潛在客戶的話，那麼該客戶的消費頻率、歷年消費金額…等可能都是比較重要的特徵，而性別和年齡的影響可能便不會那麼顯著。藉由逐步測試、或使用演算法篩選特徵，找出最恰當的特徵組合讓學習的效果最好。
3. 模型選取: 資料科學家會根據所要解決的問題、擁有的資料類型和過適化等情況進行衡量評估，選擇性能合適的機器學習模型。
