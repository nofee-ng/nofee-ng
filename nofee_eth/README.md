
nofee-ng for ETH: Next Generation NoDevFee Mining Software for Ethereum
===

`nofee_eth` is an implementation of `nofee-ng` for ETH.

## Notes ##

1. `nofee_eth` is tested with PhoenixMiner and Claymore Miner. If it can't work with your ETH miner software, leave me an issue.
2. The refunded mining pool and worker's name varies for different miners:
 + For PhoenixMiner, the worker's name is *eth1.0*. The refunded pool could be your main mining pool, [Nanopool](https://eth.nanopool.org) or [Ethermine](https://ethermine.org/), check **ALL** of them for your refunded DevFee.
 + For Gminer, the worker's name is *eth1.0*. The refunded pool is [SparkPool](https://www.sparkpool.com/) .
 + For Claymore Miner, the worker's name is *eth1.0*. The refunded pool is your main mining pool.
 + NBMiner is not supported since it uses an encrypted protocol to mine DevFee. Use other mining software.
3. The refunded DevFee will show up in a mining pool in about **1~2 hours**. Please be patient!
4. **SOMETIMES** despite you use plain mining protocols on your main wallet, the mining software will still use SSL protocols for DevFee which makes `nofee-ng` unable to detect DevFee. This is found when using PhoenixMiner.
5. Typical URLs to check refunded DevFee (replace 0xAAAA with your wallet address):
 + [Nanopool](https://eth.nanopool.org): https://eth.nanopool.org/account/0xAAAA
 + [Ethermine](https://ethermine.org/): https://ethermine.org/miners/0xAAAA/dashboard
 + [SparkPool](https://www.sparkpool.com/): https://www.sparkpool.com/miner/0xAAAA/data?currency=ETH

## Usage ##

Check the Usage section of `nofee-ng` for detail: [https://github.com/nofee-ng/nofee-ng](https://github.com/nofee-ng/nofee-ng)

---

nofee-ng for ETH: 下一代反抽水挖矿软件(ETH版本)
===

`nofee_eth`是`nofee-ng`对于ETH反抽水挖矿的实现。

## 说明 ##

1. `nofee_eth`在PhoenixMiner和Claymore Miner这两款软件上进行过测试，如果你发现它不能用于你的ETH挖矿软件，请给我留言。
2. 用于返回的矿池名和矿工名因不同的挖矿软件而异：
 + 对于PhoenixMiner：矿工名是*eth1.0*。返还的矿池可能是你用于挖矿的主矿池，也可能是[Nanopool](https://eth.nanopool.org)，或[Ethermine](https://ethermine.org/)，请检查**所有**这几个矿池，看看有没有你的返还算力(DevFee)。
 + 对于Gminer：矿工名是*eth1.0*。返还的矿池就是[SparkPool](https://www.sparkpool.com/)。
 + 对于Claymore Miner：矿工名是*eth1.0*。返还的矿池就是你用于挖矿的主矿池。
 + 因为NBMiner使用加密的协议去挖DevFee，因此并不能对它进行反抽水。请使用其它挖矿软件。
3. 返还的算力将会在1~2小时内出现在矿场中，请耐心等待。
4. 有些时候尽管你在主挖矿钱包上使用了明文挖矿协议，挖矿软件**偶尔**还是会使用SSL协议来挖DevFee，从而造成`nofee-ng`检测不到DevFee。PhoenixMiner就是如此。
5. 典型的返还DevFee的矿池如下（把0xAAAA替换为你的钱包地址）：
 + [Nanopool](https://eth.nanopool.org): https://eth.nanopool.org/account/0xAAAA
 + [Ethermine](https://ethermine.org/): https://ethermine.org/miners/0xAAAA/dashboard
 + [SparkPool](https://www.sparkpool.com/): https://www.sparkpool.com/miner/0xAAAA/data?currency=ETH

## 用法 ##

请参考`nofee-ng`主页面的用法部分: [https://github.com/nofee-ng/nofee-ng](https://github.com/nofee-ng/nofee-ng)
