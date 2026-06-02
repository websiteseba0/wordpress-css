WordPress Table
![alt](https://t1373458.p.clickup-attachments.com/t1373458/7f381d73-349e-48c9-8579-d2ea58a26311/Zrzut%20ekranu%202026-04-14%20o%2014.24.26.png)


```css
/* ===== Modern Table Styles ===== */
table.has-fixed-layout {
  width: 100% !important;
  border-collapse: separate !important;
  border-spacing: 0 !important;
  border-radius: 12px !important;
  overflow: hidden !important;
  box-shadow: rgba(0, 0, 0, 0.1) 0px 4px 24px !important;
  margin: 24px 0px 32px !important;
  background: #ffffff !important;
  table-layout: auto !important;
}

table.has-fixed-layout tr:first-child {
  background: linear-gradient(135deg, rgb(26, 26, 46) 0%, rgb(22, 33, 62) 50%, rgb(15, 52, 96) 100%) !important;
}

table.has-fixed-layout tr:first-child td {
  color: #ffffff !important;
  font-weight: 700 !important;
  text-transform: uppercase !important;
  letter-spacing: 0.08em !important;
  padding: 16px 20px !important;
  border: none !important;
  background: transparent !important;
}

table.has-fixed-layout tr:not(:first-child) td {
  border-top: none;
  border-right: none;
  border-left: none;
  border-image: initial;
  padding: 14px 20px !important;
  color: rgb(51, 65, 85) !important;
  border-bottom: 1px solid rgb(232, 237, 245) !important;
  vertical-align: middle !important;
  line-height: 1.5 !important;
  background: transparent !important;
}

table.has-fixed-layout tr:nth-child(2n) {
  background-color: rgb(247, 249, 252) !important;
}

table.has-fixed-layout tr:nth-child(2n+1):not(:first-child) {
  background-color: #ffffff !important;
}

table.has-fixed-layout tr:not(:first-child):hover {
  background-color: rgb(238, 243, 251) !important;
  transition: background-color 0.2s !important;
}

table.has-fixed-layout tr:not(:first-child) td:first-child {
  font-weight: 600 !important;
  color: rgb(26, 26, 46) !important;
}

table.has-fixed-layout tr:last-child td {
  border-bottom: none !important;
}

table.has-fixed-layout tr:not(:first-child) td:nth-child(2) {
  font-weight: 700 !important;
  color: rgb(15, 52, 96) !important;
}

table.has-fixed-layout tr:first-child td:first-child {
  border-top-left-radius: 12px !important;
}

table.has-fixed-layout tr:first-child td:last-child {
  border-top-right-radius: 12px !important;
}

table.has-fixed-layout tr:last-child td:first-child {
  border-bottom-left-radius: 12px !important;
}

table.has-fixed-layout tr:last-child td:last-child {
  border-bottom-right-radius: 12px !important;
}

table.has-fixed-layout a {
  color: rgb(15, 52, 96) !important;
  font-weight: 600 !important;
  text-decoration: none !important;
  border-bottom: 1.5px solid rgba(15, 52, 96, 0.25) !important;
  padding-bottom: 1px !important;
}

table.has-fixed-layout a:hover {
  color: rgb(233, 69, 96) !important;
  border-color: rgb(233, 69, 96) !important;
}
```

## WordPress Thead Header

```css
/* ===== Modern Table Styles ===== */
table.has-fixed-layout {
  width: 100% !important;
  border-collapse: collapse !important;
  box-shadow: 0 4px 24px rgba(0,0,0,0.1) !important;
  border-radius: 12px !important;
  overflow: hidden !important;
  margin: 24px 0 32px !important;
  background: #ffffff !important;
}

/* Table Header */
table.has-fixed-layout th {
  background: #1a1a2e !important;
  color: #ffffff !important;
  font-weight: 700 !important;
  text-transform: uppercase !important;
  letter-spacing: 0.08em !important;
  padding: 16px 20px !important;
  text-align: left !important;
  border: none !important;
}

table.has-fixed-layout td {
  padding: 14px 20px !important;
  border-bottom: 1px solid #e8edf5 !important;
  border-top: none !important;
  border-left: none !important;
  border-right: none !important;
  color: #334155 !important;
  vertical-align: middle !important;
  line-height: 1.5 !important;
}

table.has-fixed-layout tr:nth-child(even) td {
  background: #f7f9fc !important;
}

table.has-fixed-layout tr:nth-child(odd) td {
  background: #ffffff !important;
}

table.has-fixed-layout tr:hover td {
  background: #eef3fb !important;
  transition: background-color 0.2s !important;
}

table.has-fixed-layout tr:last-child td {
  border-bottom: none !important;
}

table.has-fixed-layout td:first-child {
  font-weight: 600 !important;
  color: #1a1a2e !important;
}

table.has-fixed-layout a {
  color: #0f3460 !important;
  font-weight: 600 !important;
  text-decoration: none !important;
  border-bottom: 1.5px solid rgba(15, 52, 96, 0.25) !important;
  padding-bottom: 1px !important;
}

table.has-fixed-layout a:hover {
  color: #e94560 !important;
  border-color: #e94560 !important;
}
```

## WordPress Table with Header

```css
/* ===== Modern Table Styles ===== */
table.has-fixed-layout {
  border-collapse: collapse !important;
  width: 100% !important;
  box-shadow: 0 2px 16px rgba(0,0,0,0.08) !important;
  border-radius: 10px !important;
  overflow: hidden !important;
}

table.has-fixed-layout th {
  background: #1a1a2e !important;
  color: #fff !important;
  padding: 14px 20px !important;
  text-align: left !important;
  font-size: 13px !important;
  letter-spacing: 0.06em !important;
  text-transform: uppercase !important;
}

table.has-fixed-layout td {
  padding: 13px 20px !important;
  border-bottom: 1px solid #eef0f4 !important;
  color: #334155 !important;
  line-height: 1.5 !important;
}

table.has-fixed-layout tr:nth-child(even) td { background: #f8fafc !important; }
table.has-fixed-layout tr:last-child td { border-bottom: none !important; }
table.has-fixed-layout tr:hover td { background: #eef3fb !important; }
table.has-fixed-layout td:first-child { font-weight: 600 !important; color: #1a1a2e !important; }
```

```css
table {
  width: 100% !important;
  border-collapse: collapse !important;
  margin: 2.5rem 0 !important;
  border-radius: 8px !important;
  overflow: hidden !important;
  box-shadow: 0 2px 12px rgba(0,0,0,0.08) !important;
}

table th {
  background: #1a1a2e !important;
  color: #ffffff !important;
  padding: 14px 16px !important;
  text-align: left !important;
  font-weight: 700 !important;
  border: none !important;
}

table td {
  padding: 12px 16px !important;
  border-bottom: 1px solid #e8edf5 !important;
  border-top: none !important;
  border-left: none !important;
  border-right: none !important;
  color: #334155 !important;
}

table tr:nth-child(even) td {
  background: #f7f9fc !important;
}

table tr:nth-child(odd) td {
  background: #ffffff !important;
}

table tr:hover td {
  background: #eef3fb !important;
}

table tr:last-child td {
  border-bottom: none !important;
}
```
