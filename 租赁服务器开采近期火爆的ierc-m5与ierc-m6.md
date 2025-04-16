### ierc-m6 早期挖矿指南（当前进度 0.319%）

**实时进度查询**（需科学上网）：  
[https://www.ierc20.com/tick/ierc-m6](https://www.ierc20.com/tick/ierc-m6)

---

#### ⚠️ 重要安全提示
1. **禁用网页版挖矿**：需导入私钥存在盗币风险（群内已有案例）  
2. **设备要求**：家用电脑性能不足，需租用海外GPU服务器  
3. **网络限制**：阿里云/腾讯云无法访问外网，推荐使用国际GPU租赁平台  

---

### 🚀 四步启动挖矿

#### 1️⃣ 注册服务器平台
- **Vast.ai 注册链接**（含推荐码）：  
  [https://cloud.vast.ai](https://cloud.vast.ai/?ref_id=88254)

#### 2️⃣ 服务器租用指南
- **配置参考**（直接跳转第三部分）：  
  [https://heiyetouzi.xyz/minequainetwork/#toc-heading-15](https://heiyetouzi.xyz/minequainetwork/#toc-heading-15)  
- **推荐机型**：RTX 3080/3090（约 $0.15/小时）  
- **操作入口**：控制台左侧 » INSTANCES » 点击 Open/Connecting  
  ![](https://ac63e02.webp.li/ierc20m6-001.png)  
  ![](https://ac63e02.webp.li/ierc20m6-002.png)

#### 3️⃣ 环境部署命令
```bash
apt update && apt install nodejs npm vim -y
npm install n -g
n stable
hash -r
node -v 
git clone https://github.com/IErcOrg/ierc-miner-js
cd ierc-miner-js
npm i -g yarn
yarn install
```

#### 4️⃣ 配置文件修改
```bash
vim tokens.json
```
**替换为以下内容**（按 `i` 进入编辑，粘贴后 `Esc` → `:wq` 保存）：
```json
{
  "ierc-m4": { "workc": "0x0000", "amt": "1000" },
  "ierc-m5": { "workc": "0x00000", "amt": "1000" },
  "ierc-m6": { "workc": "0x000000", "amt": "1000" }
}
```

---

### ⛏️ 启动挖矿
```bash
yarn cli wallet --set 你的ETH私钥
yarn cli mine ierc-m6 --account 你的ETH地址
```
![](https://gcore.jsdelivr.net/gh/btcltceth/blogassets@v0.2.26/b/img/ierc20m6-003.png)

---

### 💰 收益查看与交易
- **链上查询**（需科学上网）：  
  [https://www.ierc20.com/tick/ierc-m6](https://www.ierc20.com/tick/ierc-m6)  
- **当前市价**：1 ierc-m6 ≈ 10 USDT  
- **多机策略**：可批量租用服务器提升算力  

![](https://ac63e02.webp.li/ierc20m6-004.png)  
![](https://ac63e02.webp.li/ierc20m6-005.png)

---

### 延伸阅读
[2025中国十大虚拟币交易所排名🔥](https://btc8848.com/top-10-exchanges/)  
[币圈真实暴富/暴雷故事](https://heiyetouzi.xyz/biquanstory001/)

---

#### 🔍 热门搜索
比特币购买 | POW挖矿 | ierc挖矿 | 交易所注册 | OKX下载 | 币安App | 合约交易 | Web3空投 | NFT钱包 | 节点质押 | 杠杆爆仓 | 铭文铸造 | btc8848.com | heiyetouzi.xyz