# iOS-Unit-Test-Thoughts

## 寫 iOS test 學習心得

  一位好的工程師，少不了寫測試的習慣，更能確保自己 code 的品質，雖然有時候開發週期很趕，或者是需求變化很快，像是今天才 release 的功能，結果兩週後就要砍掉，這就大大打擊我們想寫測試的這件事，感覺成本很高，也要要花時間維護，跟著新功能更新測試的 code ，但是，假如沒有「測試」，原本很猛的 app ，可能就一些小疏失或一些小 bug 變得慘不忍睹，所以為了追求高品質的軟體，我們是時候一起面對寫測試這件事吧 💪🏾


## 首先是 FIRST
*FIRST* 是一套簡單明瞭的單元測試標準：
* Fast：寫的測試可以很快完成，這樣在跑測試時才不會花太多時間。
* Independent / Isolated：測試之間不要互相依賴，應該是各自獨立。
* Repateable：每次 run test 得到的結果應該都一樣。但外部數據和併發問題可能會導致測試結果不一樣。
* Self-validating：測試應該是全自動化。測試結果應該就只有 "pass" 或 "fail" 而已，不用去看 log 之類的東西才知道測試結果。
* Timely：理想的狀況是，在寫您的產品 code 之前，應該就先寫測試了，這被稱為 TDD (test-driven development 測試驅動開發)。




######  參考了
* https://qualitycoding.org
* https://www.raywenderlich.com/21020457-ios-unit-testing-and-ui-testing-tutorial
