My Eth-wallet
=============

基于web3.js和ethers.js的以太坊钱包。

目前已完成的功能：

* 三种方式（json格式文件、12个随机词汇、私钥）创建钱包
* 向目的地址发送以太币

使用方法：

* 在使用之前需要在本地建立测试链环境，建议使用ganache
* 在浏览器中打开index.html文件
* index.html的首页即为创建钱包界面，可以通过三种方式创建钱包
* 钱包创建成功后会进入发送交易页面，钱包创建失败的错误信息会在终端显示
* 交易发送成功会在浏览器命令行显示交易的哈希值，凭借这个哈希值可以在ganache中查找到交易信息。
