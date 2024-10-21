


调整vscode gitblame 
宽度、日期格式等都可以自定义，设置 - Gitlens - Blame: Format
settings.json 搜索两个配置项

"gitlens.blame.format": "${author|12?} ${date|12-}",
"gitlens.blame.dateFormat": "YYYY-MM-DD",


ctrl shift p  blame 打开
