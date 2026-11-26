# ロジック やる気

立ち回り検討

## 私がスターあり

```mermaid
swimlane-beta TD
subgraph l10 [残りターン9]
	y0[私がスター]
end
subgraph l9 [残りターン8<br >+1]
	y1[やる気+]
end
subgraph l8 [残りターン7<br >+1]
	y2[やる気+]
end
subgraph l7 [残りターン6<br >+1]
	y3[やる気+]
end
subgraph l6 [残りターン5<br >+1]
	y4[やる気+]
end
subgraph l5 [残りターン4<br >+1]
	Bse[せのびの魔法]==>Cdd[デイドリーミング]
end
subgraph l4 [残りターン3<br >+1]
	Bse1[元気+2]
	Cdd1[95%パラメータ上昇]
end
subgraph l3 [残りターン2<br >+1]
	Bse2[元気+2]
	Cdd2[95%パラメータ上昇]
end
subgraph l2 [残りターン1<br >+1]
	あの時の約束
	Bse3[元気+2]
	Cdd3[95%パラメータ上昇]
	
end
subgraph l1 [残りターン1]
	届いて
	Bse4[280%パラメータ上昇]
	Cdd4[95%パラメータ上昇]
end
Cdd-->Cdd1-->Cdd2-->Cdd3-->Cdd4
Bse-->Bse1-->Bse2-->Bse3-->Bse4

```

## 星南 ハッピーミルフィーユ

```mermaid
swimlane-beta TD
subgraph l10 [残りターン9 <br />&nbsp;]
	y0[私がスター]
end
subgraph l9 [残りターン8<br >+1]
	y1[やる気+]
end
subgraph l8 [残りターン7<br >+1]
	y2[やる気+]
end
subgraph l7 [残りターン6<br >+1]
	y3[やる気+]
end
subgraph l6 [残りターン5<br >+1]
	0Drink1[初星エキス]==>0se[せのびの魔法]
end
subgraph l5 [残りターン4<br >+1]
	0se1[元気+2]
	1dd[デイドリーミング]==>4aa[あなたにあげる]
end
subgraph l4 [残りターン3<br >+1]
	0se2[元気+2]
	1dd1[95%パラメータ上昇]
	4aa1[ターン終了時元気の60%]
end
subgraph l3 [残りターン2<br >+1]
	0se3[元気+2]
	1dd2[95%パラメータ上昇]
	4aa2[ターン終了時元気の60%]
end
subgraph l2 [残りターン1<br >+1]
	0se4[280%パラメータ上昇]
	1dd3[95%パラメータ上昇]
	3a[あの時の約束]
	4aa3[ターン終了時元気の60%]
end
subgraph l1 [残りターン1 <br />&nbsp;]
	1dd4[95%パラメータ上昇]
	3T[届いて]
end

0se-->0se1-->0se2-->0se3-->0se4
1dd-->1dd1-->1dd2-->1dd3-->1dd4
4aa-->4aa1-->4aa2-->4aa3
```
