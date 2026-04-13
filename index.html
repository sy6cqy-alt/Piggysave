<!DOCTYPE html>

<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="default">
<meta name="apple-mobile-web-app-title" content="小金库">
<title>小金库</title>
<style>
:root {
  --bg: #F8F9FA;
  --bg-card: #FFFFFF;
  --bg-input: #F8F9FA;
  --bg-tab: #FFFFFF;
  --border: rgba(0,0,0,.08);
  --border-strong: rgba(0,0,0,.12);
  --text: #1A1A1A;
  --text-sub: #6E7681;
  --text-placeholder: #ADB5BD;
  --accent-s: #34D399;
  --accent-d: #FB923C;
  --accent-f: #8B5CF6;
  --accent-g: #D4A017;
  --accent-g-light: #F5E6C0;
  --accent-home: #1A1A1A;
  --safe-top: env(safe-area-inset-top);
  --safe-bot: env(safe-area-inset-bottom);
  --r: 20px;
  --shadow: 0 2px 12px rgba(0,0,0,.06);
  --shadow-strong: 0 4px 20px rgba(0,0,0,.08);
}
*{margin:0;padding:0;box-sizing:border-box;-webkit-tap-highlight-color:transparent;
  font-family:-apple-system,BlinkMacSystemFont,'PingFang SC','SF Pro Display',sans-serif;}
body{background:var(--bg);color:var(--text);min-height:100vh;
  padding-top:var(--safe-top);padding-bottom:calc(80px + var(--safe-bot));
  overflow-x:hidden;}

.page{display:none}.page.active{display:block}

.header{padding:28px 24px 16px;display:flex;justify-content:space-between;align-items:flex-start;}
.header-meta{font-size:13px;color:var(–text-sub);margin-bottom:4px;letter-spacing:.5px;}
.header-title{font-size:28px;font-weight:800;letter-spacing:-.5px;}
.header-btn{width:44px;height:44px;border-radius:14px;background:var(–bg-card);
border:1px solid var(–border);display:flex;align-items:center;justify-content:center;
font-size:20px;cursor:pointer;transition:all .2s;box-shadow:var(–shadow);}
.header-btn:hover{background:var(–bg);transform:scale(1.08);}
.header-btn:active{transform:scale(.94);}

.hero{margin:0 16px 20px;
background:linear-gradient(135deg,#F1F5F9 0%,#E2E8F0 100%);
border:1px solid var(–border);
border-radius:28px;padding:28px;
color:var(–text);position:relative;overflow:hidden;box-shadow:var(–shadow);}
.hero::before{content:’’;position:absolute;top:-50px;right:-50px;width:180px;height:180px;
border-radius:50%;background:rgba(139,92,246,.06);}
.hero::after{content:’’;position:absolute;bottom:-60px;left:-20px;width:200px;height:200px;
border-radius:50%;background:rgba(52,211,153,.06);}
.hero-label{font-size:11px;font-weight:700;color:var(–text-sub);letter-spacing:1.5px;text-transform:uppercase;}
.hero-amount{font-size:48px;font-weight:900;letter-spacing:-2px;margin:8px 0 28px;line-height:1;color:var(–text);}
.hero-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:0;}
.hero-stat{border-left:1px solid var(–border);padding:0 0 0 14px;}
.hero-stat:first-child{border-left:none;padding-left:0;}
.hero-stat-val{font-size:15px;font-weight:700;margin-bottom:3px;color:var(–text);}
.hero-stat-label{font-size:11px;color:var(–text-sub);font-weight:600;}

.section-hd{display:flex;justify-content:space-between;align-items:center;
padding:8px 24px 14px;}
.section-title{font-size:13px;font-weight:700;color:var(–text-sub);letter-spacing:1px;text-transform:uppercase;}
.add-fab{display:flex;align-items:center;gap:6px;padding:8px 16px;border-radius:50px;
border:none;font-size:13px;font-weight:700;cursor:pointer;
transition:transform .2s cubic-bezier(.34,1.56,.64,1),box-shadow .2s,filter .2s;
-webkit-appearance:none;box-shadow:var(–shadow);}
.add-fab:hover{transform:scale(1.07);}
.add-fab:active{transform:scale(.93);}
.add-fab.s{background:var(–accent-s);color:#FFFFFF;box-shadow:0 6px 20px rgba(52,211,153,.25);}
.add-fab.s:hover{box-shadow:0 10px 28px rgba(52,211,153,.35);}
.add-fab.d{background:var(–accent-d);color:#FFFFFF;box-shadow:0 6px 20px rgba(251,146,60,.25);}
.add-fab.d:hover{box-shadow:0 10px 28px rgba(251,146,60,.35);}
.add-fab.f{background:var(–accent-f);color:#FFFFFF;box-shadow:0 6px 20px rgba(139,92,246,.25);}
.add-fab.f:hover{box-shadow:0 10px 28px rgba(139,92,246,.35);}
.add-fab.g{background:var(–accent-g);color:#FFFFFF;box-shadow:0 6px 20px rgba(212,160,23,.25);}
.add-fab.g:hover{box-shadow:0 10px 28px rgba(212,160,23,.35);}

.card-list{padding:0 16px;display:flex;flex-direction:column;gap:12px;}
.card{background:var(–bg-card);border:1px solid var(–border);border-radius:var(–r);
padding:20px;cursor:default;box-shadow:var(–shadow);
transition:transform .2s cubic-bezier(.34,1.56,.64,1),box-shadow .2s,border-color .2s;}
.card:hover{transform:translateY(-2px);box-shadow:var(–shadow-strong);border-color:var(–border-strong);}
.card:active{transform:translateY(0) scale(.99);}

.card-top{display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:14px;}
.card-name{font-size:17px;font-weight:700;flex:1;margin-right:10px;word-break:break-all;}
.card-amount{font-size:20px;font-weight:800;white-space:nowrap;}

.card-tags{display:flex;flex-wrap:wrap;gap:8px;margin-bottom:14px;}
.tag{padding:4px 10px;border-radius:8px;font-size:12px;font-weight:600;
background:var(–bg-input);color:var(–text-sub);}
.tag.accent-s{background:rgba(52,211,153,.12);color:var(–accent-s);}
.tag.accent-d{background:rgba(251,146,60,.12);color:var(–accent-d);}
.tag.accent-f{background:rgba(139,92,246,.12);color:var(–accent-f);}
.tag.accent-g{background:rgba(212,160,23,.14);color:var(–accent-g);}
.tag.warn{background:rgba(255,184,28,.12);color:#F59E0B;}
.tag.over{background:rgba(239,68,68,.12);color:#EF4444;}

.card-actions{display:flex;gap:8px;justify-content:flex-end;}
.act-btn{padding:7px 16px;border-radius:10px;font-size:12px;font-weight:700;
border:none;cursor:pointer;-webkit-appearance:none;
transition:transform .18s cubic-bezier(.34,1.56,.64,1),filter .15s;}
.act-btn:hover{transform:scale(1.1);filter:brightness(1.1);}
.act-btn:active{transform:scale(.92);}
.act-btn.edit-s{background:rgba(52,211,153,.15);color:var(–accent-s);}
.act-btn.edit-d{background:rgba(251,146,60,.15);color:var(–accent-d);}
.act-btn.edit-f{background:rgba(139,92,246,.15);color:var(–accent-f);}
.act-btn.edit-g{background:rgba(212,160,23,.15);color:var(–accent-g);}
.act-btn.del{background:rgba(239,68,68,.12);color:#EF4444;}

.empty{text-align:center;padding:60px 24px;}
.empty-icon{font-size:56px;margin-bottom:14px;opacity:.6;}
.empty-text{font-size:15px;color:var(–text-sub);margin-bottom:20px;}
.empty-cta{display:inline-block;padding:12px 24px;border-radius:50px;font-size:14px;
font-weight:700;cursor:pointer;border:none;-webkit-appearance:none;
transition:transform .2s cubic-bezier(.34,1.56,.64,1),box-shadow .2s;box-shadow:var(–shadow);}
.empty-cta:hover{transform:scale(1.06);}
.empty-cta:active{transform:scale(.94);}
.empty-cta.s{background:var(–accent-s);color:#FFFFFF;box-shadow:0 6px 20px rgba(52,211,153,.25);}
.empty-cta.d{background:var(–accent-d);color:#FFFFFF;box-shadow:0 6px 20px rgba(251,146,60,.25);}
.empty-cta.f{background:var(–accent-f);color:#FFFFFF;box-shadow:0 6px 20px rgba(139,92,246,.25);}
.empty-cta.g{background:var(–accent-g);color:#FFFFFF;box-shadow:0 6px 20px rgba(212,160,23,.25);}

.expire-strip{margin:0 16px 16px;background:rgba(255,184,28,.08);border:1px solid rgba(255,184,28,.2);
border-radius:var(–r);padding:16px 20px;box-shadow:var(–shadow);}
.expire-strip-title{font-size:11px;font-weight:700;color:#F59E0B;letter-spacing:1px;
text-transform:uppercase;margin-bottom:12px;}
.expire-item{display:flex;justify-content:space-between;align-items:center;padding:8px 0;
border-top:1px solid rgba(255,184,28,.1);}
.expire-item:first-of-type{border-top:none;padding-top:0;}
.expire-name{font-size:14px;font-weight:600;}
.expire-meta{font-size:12px;color:var(–text-sub);margin-top:2px;}
.expire-val{text-align:right;}
.expire-amt{font-size:15px;font-weight:700;}
.expire-days{font-size:12px;color:#F59E0B;margin-top:2px;font-weight:600;}

/* ─── TABBAR ─── */
.tabbar{position:fixed;bottom:0;left:0;right:0;
background:var(–bg-tab);backdrop-filter:blur(20px);-webkit-backdrop-filter:blur(20px);
border-top:1px solid var(–border);
display:flex;padding-bottom:var(–safe-bot);z-index:99;box-shadow:0 -2px 12px rgba(0,0,0,.05);}
.tab{flex:1;padding:12px 0 10px;display:flex;flex-direction:column;align-items:center;
gap:4px;cursor:pointer;color:var(–text-sub);
transition:color .2s,transform .2s cubic-bezier(.34,1.56,.64,1);}
.tab:hover{transform:translateY(-2px);}
.tab:active{transform:scale(.9);}
.tab.active{color:var(–text);}
.tab-icon{font-size:22px;line-height:1;}
.tab-dot{width:4px;height:4px;border-radius:2px;background:currentColor;
opacity:0;transition:opacity .2s,width .2s;}
.tab.active .tab-dot{opacity:1;width:16px;}
.tab-label{font-size:10px;font-weight:700;letter-spacing:.5px;}

.tab[data-page=“saving”].active{color:var(–accent-s);}
.tab[data-page=“deposit”].active{color:var(–accent-d);}
.tab[data-page=“finance”].active{color:var(–accent-f);}
.tab[data-page=“gold”].active{color:var(–accent-g);}

/* ─── BOTTOM SHEET ─── */
.sheet-mask{position:fixed;inset:0;background:rgba(0,0,0,.4);z-index:999;
display:none;align-items:flex-end;
backdrop-filter:blur(4px);-webkit-backdrop-filter:blur(4px);}
.sheet-mask.show{display:flex;}
.sheet{width:100%;background:var(–bg-card);border-radius:28px 28px 0 0;
padding:0 0 0;
padding-bottom:calc(32px + var(–safe-bot));
max-height:92vh;overflow-y:scroll;
-webkit-overflow-scrolling:touch;overscroll-behavior:contain;box-shadow:0 -4px 20px rgba(0,0,0,.1);}
.sheet-handle{width:36px;height:4px;background:var(–border-strong);border-radius:2px;
margin:14px auto 0;}
.sheet-header{padding:20px 24px 16px;display:flex;justify-content:space-between;align-items:center;}
.sheet-title{font-size:22px;font-weight:800;letter-spacing:-.5px;}
.sheet-close{width:32px;height:32px;border-radius:10px;background:var(–bg-input);
border:none;color:var(–text-sub);font-size:18px;cursor:pointer;
display:flex;align-items:center;justify-content:center;
transition:transform .18s,background .15s;
-webkit-user-select:none;user-select:none;}
.sheet-close:hover{background:var(–bg);transform:scale(1.1);}
.sheet-close:active{transform:scale(.9);}

.ftab-group{display:flex;gap:8px;padding:0 24px 20px;overflow-x:auto;scrollbar-width:none;}
.ftab-group::-webkit-scrollbar{display:none;}
.ftab{padding:9px 18px;border-radius:50px;font-size:13px;font-weight:700;
border:1.5px solid var(–border);color:var(–text-sub);white-space:nowrap;cursor:pointer;
transition:all .2s;background:transparent;
-webkit-user-select:none;user-select:none;}
.ftab:hover{border-color:var(–border-strong);color:var(–text);}
.ftab:active{transform:scale(.95);}
.ftab.active-s{background:rgba(52,211,153,.15);border-color:var(–accent-s);color:var(–accent-s);}
.ftab.active-d{background:rgba(251,146,60,.15);border-color:var(–accent-d);color:var(–accent-d);}
.ftab.active-f{background:rgba(139,92,246,.15);border-color:var(–accent-f);color:var(–accent-f);}
.ftab.active-g{background:rgba(212,160,23,.15);border-color:var(–accent-g);color:var(–accent-g);}

.form-panel{display:none;padding:0 24px;}
.form-panel.active{display:block;}
.fg{margin-bottom:18px;}
.fg label{display:block;font-size:12px;font-weight:700;color:var(–text-sub);
letter-spacing:.8px;text-transform:uppercase;margin-bottom:8px;}
.fi,.fs{width:100%;padding:16px 18px;background:var(–bg-input);border:1.5px solid var(–border);
border-radius:14px;font-size:16px;color:var(–text);outline:none;
-webkit-appearance:none;appearance:none;
transition:border-color .2s,box-shadow .2s;}
.fi:focus,.fs:focus{border-color:var(–border-strong);box-shadow:0 0 0 3px rgba(0,0,0,.04);}
.fi::placeholder{color:var(–text-placeholder);}
.fi.focus-s:focus{border-color:var(–accent-s);box-shadow:0 0 0 3px rgba(52,211,153,.1);}
.fi.focus-d:focus{border-color:var(–accent-d);box-shadow:0 0 0 3px rgba(251,146,60,.1);}
.fi.focus-f:focus{border-color:var(–accent-f);box-shadow:0 0 0 3px rgba(139,92,246,.1);}
.fi.focus-g:focus{border-color:var(–accent-g);box-shadow:0 0 0 3px rgba(212,160,23,.1);}

.submit-btn{display:block;width:100%;margin-top:28px;padding:18px 0;border-radius:16px;
font-size:17px;font-weight:800;color:rgba(255,255,255,.4);border:none;cursor:pointer;
-webkit-appearance:none;letter-spacing:.3px;
transition:background .25s,color .25s,box-shadow .2s,transform .18s cubic-bezier(.34,1.56,.64,1);
-webkit-user-select:none;user-select:none;}
.submit-btn:hover{transform:scale(1.02);}
.submit-btn:active{transform:scale(.97);}
.submit-btn.s{background:rgba(52,211,153,.25);}
.submit-btn.d{background:rgba(251,146,60,.25);}
.submit-btn.f{background:rgba(139,92,246,.25);}
.submit-btn.g{background:rgba(212,160,23,.25);}
.submit-btn.s.ready{background:var(–accent-s);color:#FFFFFF;box-shadow:0 8px 24px rgba(52,211,153,.25);}
.submit-btn.d.ready{background:var(–accent-d);color:#FFFFFF;box-shadow:0 8px 24px rgba(251,146,60,.25);}
.submit-btn.f.ready{background:var(–accent-f);color:#FFFFFF;box-shadow:0 8px 24px rgba(139,92,246,.25);}
.submit-btn.g.ready{background:var(–accent-g);color:#FFFFFF;box-shadow:0 8px 24px rgba(212,160,23,.25);}

.confirm-mask{position:fixed;inset:0;background:rgba(0,0,0,.4);z-index:1999;
display:none;align-items:center;justify-content:center;padding:32px;
backdrop-filter:blur(8px);-webkit-backdrop-filter:blur(8px);}
.confirm-mask.show{display:flex;}
.confirm-box{background:var(–bg-card);border:1px solid var(–border);border-radius:24px;
padding:32px 24px 24px;width:100%;max-width:320px;text-align:center;box-shadow:var(–shadow-strong);}
.confirm-icon{font-size:40px;margin-bottom:12px;}
.confirm-title{font-size:18px;font-weight:800;margin-bottom:6px;}
.confirm-desc{font-size:14px;color:var(–text-sub);margin-bottom:24px;}
.confirm-btns{display:flex;gap:10px;}
.confirm-btn{flex:1;padding:14px 0;border-radius:14px;font-size:15px;font-weight:700;
border:none;cursor:pointer;-webkit-appearance:none;
transition:transform .18s cubic-bezier(.34,1.56,.64,1),filter .15s;
-webkit-user-select:none;user-select:none;}
.confirm-btn:hover{transform:scale(1.04);filter:brightness(1.08);}
.confirm-btn:active{transform:scale(.95);}
.confirm-btn.cancel{background:var(–bg-input);color:var(–text-sub);}
.confirm-btn.danger{background:#EF4444;color:#fff;}

.spacer{height:24px;}

/* ─── GOLD PAGE ─── */
.gold-hero{margin:0 16px 20px;
background:linear-gradient(135deg,#FEF9E7 0%,#FDF0C0 50%,#F9E07A 100%);
border:1px solid rgba(212,160,23,.2);
border-radius:28px;padding:24px;
position:relative;overflow:hidden;box-shadow:0 4px 20px rgba(212,160,23,.12);}
.gold-hero::before{content:‘✦’;position:absolute;top:12px;right:20px;
font-size:48px;opacity:.08;color:var(–accent-g);}
.gold-hero-label{font-size:11px;font-weight:700;color:rgba(139,100,0,.6);letter-spacing:1.5px;text-transform:uppercase;margin-bottom:6px;}
.gold-price-row{display:flex;align-items:baseline;gap:10px;margin-bottom:4px;}
.gold-price{font-size:38px;font-weight:900;letter-spacing:-1px;color:#8B6200;}
.gold-unit{font-size:14px;font-weight:700;color:rgba(139,98,0,.6);}
.gold-change{font-size:14px;font-weight:700;padding:3px 10px;border-radius:8px;}
.gold-change.up{background:rgba(52,211,153,.15);color:#059669;}
.gold-change.down{background:rgba(239,68,68,.1);color:#DC2626;}
.gold-sync-row{display:flex;align-items:center;justify-content:space-between;margin-top:14px;padding-top:14px;border-top:1px solid rgba(212,160,23,.15);}
.gold-sync-info{font-size:12px;color:rgba(139,98,0,.55);font-weight:600;}
.gold-sync-btn{padding:8px 18px;background:var(–accent-g);color:#fff;border:none;
border-radius:50px;font-size:12px;font-weight:700;cursor:pointer;
transition:transform .2s,box-shadow .2s;box-shadow:0 4px 12px rgba(212,160,23,.3);}
.gold-sync-btn:hover{transform:scale(1.06);}
.gold-sync-btn:active{transform:scale(.94);}
.gold-sync-btn:disabled{opacity:.5;cursor:not-allowed;transform:none;}

.gold-stat-row{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-top:16px;}
.gold-stat-card{background:rgba(255,255,255,.7);border-radius:14px;padding:12px 14px;
border:1px solid rgba(212,160,23,.15);}
.gold-stat-label{font-size:10px;font-weight:700;color:rgba(139,98,0,.5);letter-spacing:.8px;margin-bottom:4px;}
.gold-stat-val{font-size:16px;font-weight:800;color:#8B6200;}

/* ─── FINANCE SYNC ─── */
.sync-strip{margin:0 16px 16px;background:rgba(139,92,246,.05);
border:1px solid rgba(139,92,246,.15);border-radius:16px;padding:14px 18px;
display:flex;align-items:center;justify-content:space-between;gap:12px;}
.sync-strip-left{flex:1;}
.sync-strip-title{font-size:12px;font-weight:700;color:var(–accent-f);margin-bottom:2px;}
.sync-strip-sub{font-size:11px;color:var(–text-sub);}
.sync-all-btn{padding:8px 16px;background:var(–accent-f);color:#fff;border:none;
border-radius:50px;font-size:12px;font-weight:700;cursor:pointer;white-space:nowrap;
transition:transform .2s,box-shadow .2s;box-shadow:0 4px 12px rgba(139,92,246,.25);}
.sync-all-btn:hover{transform:scale(1.06);}
.sync-all-btn:active{transform:scale(.94);}

.fund-sync-row{display:flex;align-items:center;gap:8px;margin-top:8px;padding-top:10px;
border-top:1px solid var(–border);}
.fund-sync-badge{font-size:11px;font-weight:700;padding:3px 9px;border-radius:6px;}
.fund-sync-badge.today{background:rgba(52,211,153,.12);color:var(–accent-s);}
.fund-sync-badge.stale{background:rgba(255,184,28,.12);color:#F59E0B;}
.fund-sync-badge.never{background:rgba(239,68,68,.1);color:#EF4444;}
.fund-nav-input-row{display:flex;align-items:center;gap:8px;margin-top:8px;}
.fund-nav-input-row input{flex:1;padding:10px 14px;border:1.5px solid var(–border);
border-radius:10px;font-size:14px;background:var(–bg-input);color:var(–text);outline:none;}
.fund-nav-input-row input:focus{border-color:var(–accent-f);}
.fund-nav-save-btn{padding:10px 16px;background:var(–accent-f);color:#fff;border:none;
border-radius:10px;font-size:13px;font-weight:700;cursor:pointer;}

/* ─── JD GOLD ─── */
.jd-gold-card{margin:0 16px 16px;background:linear-gradient(135deg,#FFF8E1,#FFFDE7);
border:1px solid rgba(212,160,23,.2);border-radius:var(–r);padding:20px;box-shadow:var(–shadow);}
.jd-gold-header{display:flex;align-items:center;justify-content:space-between;margin-bottom:16px;}
.jd-gold-title{font-size:15px;font-weight:800;color:#7B5800;}
.jd-gold-badge{font-size:11px;padding:3px 10px;border-radius:6px;font-weight:700;
background:rgba(212,160,23,.15);color:var(–accent-g);}
.jd-holding-grid{display:grid;grid-template-columns:1fr 1fr;gap:12px;}
.jd-holding-item{background:rgba(255,255,255,.8);border-radius:12px;padding:12px 14px;
border:1px solid rgba(212,160,23,.12);}
.jd-holding-label{font-size:11px;color:rgba(139,98,0,.5);font-weight:700;margin-bottom:4px;}
.jd-holding-val{font-size:18px;font-weight:800;color:#7B5800;}

/* ─── SPIN ANIMATION ─── */
@keyframes spin{to{transform:rotate(360deg)}}
.spinning{animation:spin .8s linear infinite;display:inline-block;}

/* ─── GOLD PRICE PULSE ─── */
@keyframes pricePulse{0%{opacity:1}50%{opacity:.4}100%{opacity:1}}
.price-updating{animation:pricePulse .8s ease-in-out 2;}

/* ─── HELPER STRIP ─── */
.info-strip{margin:0 16px 12px;background:rgba(139,92,246,.04);
border:1px solid rgba(139,92,246,.1);border-radius:12px;padding:10px 14px;
font-size:12px;color:var(–text-sub);line-height:1.6;}
.info-strip b{color:var(–accent-f);}

.gold-info-strip{margin:0 16px 12px;background:rgba(212,160,23,.05);
border:1px solid rgba(212,160,23,.12);border-radius:12px;padding:10px 14px;
font-size:12px;color:rgba(139,98,0,.6);line-height:1.6;}

</style>
</head>
<body>

<!-- ═══════════════ HOME ═══════════════ -->

<div class="page active" id="page-home">
  <div class="header">
    <div>
      <div class="header-meta" id="currentDate"></div>
      <div class="header-title">小金库</div>
    </div>
    <div class="header-btn" onclick="showToast('小金库 · 你的资产管家')">
      <svg width="20" height="20" viewBox="0 0 24 24" fill="none">
        <polyline points="3,17 8,11 13,14 21,5" stroke="#1A1A1A" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        <polyline points="17,5 21,5 21,9" stroke="#1A1A1A" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        <line x1="3" y1="21" x2="21" y2="21" stroke="rgba(26,26,26,0.3)" stroke-width="1.5" stroke-linecap="round"/>
      </svg>
    </div>
  </div>

  <div id="expireReminder"></div>

  <div class="hero">
    <div class="hero-label">TOTAL ASSETS</div>
    <div class="hero-amount" id="totalAsset">¥0.00</div>
    <div class="hero-grid">
      <div class="hero-stat">
        <div class="hero-stat-val" id="totalDepositInterest">¥0.00</div>
        <div class="hero-stat-label">定期到期总收益</div>
      </div>
      <div class="hero-stat">
        <div class="hero-stat-val" id="totalFinanceProfit">¥0.00</div>
        <div class="hero-stat-label">理财收益</div>
      </div>
      <div class="hero-stat">
        <div class="hero-stat-val" id="totalGoldProfit">¥0.00</div>
        <div class="hero-stat-label">黄金收益</div>
      </div>
    </div>
  </div>

  <div class="section-hd">
    <div class="section-title">收益概览</div>
  </div>
  <div id="homeOverview" style="padding:0 16px 8px;"></div>
  <div class="spacer"></div>
</div>

<!-- ═══════════════ SAVING ═══════════════ -->

<div class="page" id="page-saving">
  <div class="header">
    <div>
      <div class="header-meta">LIQUID SAVINGS</div>
      <div class="header-title" style="color:var(--accent-s)">活期储蓄</div>
    </div>
    <button class="add-fab s" onclick="openModal('saving')">＋ 新增</button>
  </div>
  <div id="savingList"></div>
  <div class="spacer"></div>
</div>

<!-- ═══════════════ DEPOSIT ═══════════════ -->

<div class="page" id="page-deposit">
  <div class="header">
    <div>
      <div class="header-meta">FIXED DEPOSIT</div>
      <div class="header-title" style="color:var(--accent-d)">定期存款</div>
    </div>
    <button class="add-fab d" onclick="openModal('deposit')">＋ 新增</button>
  </div>
  <div id="depositList"></div>
  <div class="spacer"></div>
</div>

<!-- ═══════════════ FINANCE ═══════════════ -->

<div class="page" id="page-finance">
  <div class="header">
    <div>
      <div class="header-meta">INVESTMENTS</div>
      <div class="header-title" style="color:var(--accent-f)">理财投资</div>
    </div>
    <button class="add-fab f" onclick="openModal('finance')">＋ 新增</button>
  </div>
  <div id="financeSyncStrip"></div>
  <div id="financeList"></div>
  <div class="spacer"></div>
</div>

<!-- ═══════════════ GOLD ═══════════════ -->

<div class="page" id="page-gold">
  <div class="header">
    <div>
      <div class="header-meta">GOLD HOLDINGS</div>
      <div class="header-title" style="color:var(--accent-g)">黄金</div>
    </div>
    <button class="add-fab g" onclick="openModal('gold')">＋ 新增</button>
  </div>

  <!-- 实时金价面板 -->

  <div class="gold-hero">
    <div class="gold-hero-label">实时金价 · 人民币</div>
    <div class="gold-price-row">
      <div class="gold-price" id="goldPriceDisplay">--</div>
      <div class="gold-unit">元/克</div>
      <div class="gold-change" id="goldChangeDisplay" style="display:none"></div>
    </div>
    <div style="font-size:12px;color:rgba(139,98,0,.45);margin-bottom:4px;" id="goldPriceSource">数据来源：国际现货金价换算</div>
    <div class="gold-stat-row">
      <div class="gold-stat-card">
        <div class="gold-stat-label">持仓克重</div>
        <div class="gold-stat-val" id="goldTotalGrams">0g</div>
      </div>
      <div class="gold-stat-card">
        <div class="gold-stat-label">持仓成本</div>
        <div class="gold-stat-val" id="goldTotalCost">¥0</div>
      </div>
      <div class="gold-stat-card">
        <div class="gold-stat-label">当前市值</div>
        <div class="gold-stat-val" id="goldTotalValue">¥0</div>
      </div>
    </div>
    <div class="gold-sync-row">
      <div class="gold-sync-info" id="goldLastSync">尚未同步金价</div>
      <button class="gold-sync-btn" id="goldSyncBtn" onclick="syncGoldPrice()">🔄 同步金价</button>
    </div>
  </div>

  <div class="gold-info-strip">
    ℹ️ 金价数据通过国际金价（美元/盎司）× 汇率换算，仅供参考。<b>京东积存金</b>持仓自动跟随实时金价计算市值。
  </div>

  <!-- 京东积存金汇总卡 -->

  <div id="jdGoldSummary"></div>

  <div id="goldList"></div>
  <div class="spacer"></div>
</div>

<!-- ═══════════════ TABBAR ═══════════════ -->

<div class="tabbar">
  <div class="tab active" data-page="home">
    <div class="tab-icon">⬡</div>
    <div class="tab-dot"></div>
    <div class="tab-label">首页</div>
  </div>
  <div class="tab" data-page="saving">
    <div class="tab-icon">◈</div>
    <div class="tab-dot"></div>
    <div class="tab-label">活期</div>
  </div>
  <div class="tab" data-page="deposit">
    <div class="tab-icon">◉</div>
    <div class="tab-dot"></div>
    <div class="tab-label">定期</div>
  </div>
  <div class="tab" data-page="finance">
    <div class="tab-icon">◈</div>
    <div class="tab-dot"></div>
    <div class="tab-label">理财</div>
  </div>
  <div class="tab" data-page="gold">
    <div class="tab-icon">✦</div>
    <div class="tab-dot"></div>
    <div class="tab-label">黄金</div>
  </div>
</div>

<!-- ═══════════════ BOTTOM SHEET ═══════════════ -->

<div class="sheet-mask" id="modal">
  <div class="sheet" id="sheetContent">
    <div class="sheet-handle"></div>
    <div class="sheet-header">
      <div class="sheet-title" id="sheetTitle">新增</div>
      <button class="sheet-close" onclick="closeModal()">✕</button>
    </div>

```
<div class="ftab-group">
  <div class="ftab" data-type="saving">🌱 活期</div>
  <div class="ftab" data-type="deposit">💰 定期</div>
  <div class="ftab" data-type="finance">📈 理财</div>
  <div class="ftab" data-type="gold">✦ 黄金</div>
</div>

<input type="hidden" id="formType" value="deposit">
<input type="hidden" id="editId">

<!-- 活期 -->
<div class="form-panel" id="savingPanel">
  <div class="fg"><label>账户名称</label>
    <input class="fi focus-s" id="savingName" type="text" placeholder="微信零钱 / 余额宝…"></div>
  <div class="fg"><label>当前余额（元）</label>
    <input class="fi focus-s" id="savingBalance" type="number" inputmode="decimal" placeholder="0.00" min="0"></div>
  <div class="fg"><label>年利率（%）</label>
    <input class="fi focus-s" id="savingRate" type="number" inputmode="decimal" value="1.5" min="0"></div>
  <div class="fg"><label>账户类型</label>
    <select class="fs" id="savingType">
      <option>银行活期</option><option>货币基金</option>
      <option>微信零钱</option><option>支付宝余额宝</option><option>其他</option>
    </select></div>
  <div class="fg"><label>备注（选填）</label>
    <input class="fi focus-s" id="savingNote" type="text" placeholder=""></div>
  <button class="submit-btn s" onclick="submitForm()">保存</button>
</div>

<!-- 定期 -->
<div class="form-panel" id="depositPanel">
  <div class="fg"><label>名称</label>
    <input class="fi focus-d" id="depositName" type="text" placeholder="工行定期 / 大额存单…"></div>
  <div class="fg"><label>本金（元）</label>
    <input class="fi focus-d" id="depositAmount" type="number" inputmode="decimal" placeholder="0.00" min="0"></div>
  <div class="fg"><label>年利率（%）</label>
    <input class="fi focus-d" id="depositRate" type="number" inputmode="decimal" value="2.5" min="0"></div>
  <div class="fg"><label>开始日期</label>
    <input class="fi focus-d" id="depositStartDate" type="date"></div>
  <div class="fg"><label>期限（月）</label>
    <input class="fi focus-d" id="depositTerm" type="number" inputmode="numeric" value="12" min="1"></div>
  <button class="submit-btn d" onclick="submitForm()">保存</button>
</div>

<!-- 理财 -->
<div class="form-panel" id="financePanel">
  <div class="fg"><label>名称</label>
    <input class="fi focus-f" id="financeName" type="text" placeholder="易方达 / 华夏…"></div>
  <div class="fg"><label>投入金额（元）</label>
    <input class="fi focus-f" id="financeAmount" type="number" inputmode="decimal" placeholder="0.00" min="0"></div>
  <div class="fg"><label>当前价值（元）</label>
    <input class="fi focus-f" id="financeCurrentValue" type="number" inputmode="decimal" placeholder="0.00" min="0"></div>
  <div class="fg"><label>类型</label>
    <select class="fs" id="financeType">
      <option>基金</option><option>股票</option><option>债券</option><option>其他</option>
    </select></div>
  <div class="fg"><label>上次同步日期（自动记录）</label>
    <input class="fi focus-f" id="financeLastSync" type="date" placeholder="选择同步日期" readonly style="background:#f0f0f0;color:var(--text-sub);"></div>
  <button class="submit-btn f" onclick="submitForm()">保存</button>
</div>

<!-- 黄金 -->
<div class="form-panel" id="goldPanel">
  <div class="fg"><label>持仓名称</label>
    <input class="fi focus-g" id="goldName" type="text" placeholder="京东积存金 / 银行黄金…"></div>
  <div class="fg"><label>是否为京东积存金</label>
    <select class="fs" id="goldIsJD" onchange="toggleJDGold()">
      <option value="0">否（普通黄金）</option>
      <option value="1">是（京东积存金）</option>
    </select></div>
  <div class="fg"><label>持仓克重（克）</label>
    <input class="fi focus-g" id="goldGrams" type="number" inputmode="decimal" placeholder="0.00" min="0" step="0.01"></div>
  <div class="fg" id="goldCostPriceGroup"><label>买入均价（元/克）</label>
    <input class="fi focus-g" id="goldCostPrice" type="number" inputmode="decimal" placeholder="留空则用当前金价" min="0" step="0.01"></div>
  <div class="fg" id="goldManualValueGroup" style="display:none;"><label>当前价值（元，留空跟随实时金价）</label>
    <input class="fi focus-g" id="goldManualValue" type="number" inputmode="decimal" placeholder="留空=自动计算" min="0"></div>
  <div class="fg"><label>备注（选填）</label>
    <input class="fi focus-g" id="goldNote" type="text" placeholder=""></div>
  <button class="submit-btn g" onclick="submitForm()">保存</button>
</div>
```

  </div>
</div>

<!-- ═══════════════ CONFIRM ═══════════════ -->

<div class="confirm-mask" id="confirmMask">
  <div class="confirm-box">
    <div class="confirm-icon">⚠️</div>
    <div class="confirm-title">确认删除</div>
    <div class="confirm-desc" id="confirmDesc">删除后无法恢复</div>
    <div class="confirm-btns">
      <button class="confirm-btn cancel" onclick="closeConfirm()">取消</button>
      <button class="confirm-btn danger" id="confirmOkBtn">删除</button>
    </div>
  </div>
</div>

<!-- ═══════════════ FUND NAV SYNC MODAL ═══════════════ -->

<div class="confirm-mask" id="fundSyncMask" style="z-index:2999;">
  <div class="confirm-box" style="max-width:360px;text-align:left;">
    <div style="font-size:20px;font-weight:800;margin-bottom:6px;">📈 更新基金净值</div>
    <div style="font-size:13px;color:var(--text-sub);margin-bottom:18px;" id="fundSyncItemName">—</div>
    <div style="font-size:12px;font-weight:700;color:var(--text-sub);letter-spacing:.8px;margin-bottom:8px;">当前价值（元）</div>
    <input class="fi focus-f" id="fundSyncNewValue" type="number" inputmode="decimal" placeholder="输入最新总价值" style="margin-bottom:16px;">
    <div style="font-size:11px;color:var(--text-sub);margin-bottom:24px;">今日日期将自动记录为同步时间</div>
    <div class="confirm-btns">
      <button class="confirm-btn cancel" onclick="closeFundSync()">取消</button>
      <button class="confirm-btn" id="fundSyncOkBtn" style="background:var(--accent-f);color:#fff;">更新</button>
    </div>
  </div>
</div>

<script>
/* ─────────────── DATA ─────────────── */
let depositList = [], financeList = [], savingList = [], goldList = [];
let goldPrice = 0; // 当前金价 元/克
let goldLastSyncTime = null;
let goldLastSyncPrice = 0;
let _pendingDelete = null;
let _fundSyncItemId = null;

/* ─────────────── INIT ─────────────── */
window.onload = () => {
  initDate();
  loadData();
  bindTab();
  bindFormTab();
  bindSheetClose();
  bindSaveReady();
  renderAll();
  startExpireCheck();
  document.getElementById('depositStartDate').valueAsDate = new Date();
  // 自动尝试同步金价
  syncGoldPrice(true);
};

function startExpireCheck() {
  checkExpireItems();
  setInterval(checkExpireItems, 3600000);
}

/* ─────────────── DATE ─────────────── */
function initDate() {
  const w = ['日','一','二','三','四','五','六'], d = new Date();
  document.getElementById('currentDate').innerText =
    `${d.getFullYear()} 年 ${d.getMonth()+1} 月 ${d.getDate()} 日  星期${w[d.getDay()]}`;
}

function todayStr() {
  return new Date().toISOString().split('T')[0];
}

/* ─────────────── PERSIST ─────────────── */
function loadData() {
  try {
    depositList = JSON.parse(localStorage.getItem('xk_dep') || '[]');
    financeList = JSON.parse(localStorage.getItem('xk_fin') || '[]');
    savingList  = JSON.parse(localStorage.getItem('xk_sav') || '[]');
    goldList    = JSON.parse(localStorage.getItem('xk_gold') || '[]');
    goldPrice        = parseFloat(localStorage.getItem('xk_gold_price') || '0');
    goldLastSyncTime = localStorage.getItem('xk_gold_sync_time') || null;
    goldLastSyncPrice= parseFloat(localStorage.getItem('xk_gold_sync_price') || '0');
  } catch(e) { depositList=[]; financeList=[]; savingList=[]; goldList=[]; }
}
function save() {
  try {
    localStorage.setItem('xk_dep', JSON.stringify(depositList));
    localStorage.setItem('xk_fin', JSON.stringify(financeList));
    localStorage.setItem('xk_sav', JSON.stringify(savingList));
    localStorage.setItem('xk_gold', JSON.stringify(goldList));
    localStorage.setItem('xk_gold_price', String(goldPrice));
    localStorage.setItem('xk_gold_sync_time', goldLastSyncTime || '');
    localStorage.setItem('xk_gold_sync_price', String(goldLastSyncPrice));
  } catch(e) { showToast('⚠️ 存储失败：请关闭无痕模式'); }
}

/* ─────────────── GOLD PRICE SYNC ─────────────── */
async function syncGoldPrice(silent = false) {
  const btn = document.getElementById('goldSyncBtn');
  if (btn) { btn.disabled = true; btn.innerHTML = '<span class="spinning">↻</span> 同步中'; }

  try {
    // 用 goldapi.io 免费接口 (无需key的公开行情) → fallback 用固定汇率 + open exchange
    // 策略：尝试多个免费来源，取第一个成功的
    let pricePerGram = 0;
    let source = '';

    // 尝试来源1: frankfurter 获取汇率 + metals-api fallback
    // 实际可行的公开接口：通过 GoldAPI / commodities-api 等
    // 这里使用可靠的公开代理：allorigins + metals price
    // 来源1: 通过 open.er-api 获取 USD/CNY 汇率
    let usdCny = 7.25; // 默认值
    try {
      const fxResp = await fetch('https://open.er-api.com/v6/latest/USD', { signal: AbortSignal.timeout(5000) });
      if (fxResp.ok) {
        const fxData = await fxResp.json();
        if (fxData.rates && fxData.rates.CNY) {
          usdCny = fxData.rates.CNY;
        }
      }
    } catch(e) {}

    // 来源2: 获取黄金价格 (USD/troy oz) — 使用 metals.live 公开API
    try {
      const goldResp = await fetch('https://api.metals.live/v1/spot/gold', { signal: AbortSignal.timeout(6000) });
      if (goldResp.ok) {
        const goldData = await goldResp.json();
        // 返回格式: [{"gold": 2300.5}] 或 {"price": 2300.5}
        let usdPerOz = 0;
        if (Array.isArray(goldData) && goldData[0] && goldData[0].gold) {
          usdPerOz = goldData[0].gold;
        } else if (goldData.price) {
          usdPerOz = goldData.price;
        } else if (goldData.gold) {
          usdPerOz = goldData.gold;
        }
        if (usdPerOz > 0) {
          pricePerGram = +(usdPerOz / 31.1035 * usdCny).toFixed(2);
          source = 'metals.live';
        }
      }
    } catch(e) {}

    // 来源3 fallback: allorigins 代理 goldprice.org
    if (!pricePerGram) {
      try {
        const r = await fetch('https://api.allorigins.win/get?url=' + encodeURIComponent('https://data-asg.goldprice.org/dbXRates/CNY'), 
          { signal: AbortSignal.timeout(8000) });
        if (r.ok) {
          const d = await r.json();
          const inner = JSON.parse(d.contents);
          // xauPrice in CNY per troy oz
          if (inner.items && inner.items[0] && inner.items[0].xauPrice) {
            pricePerGram = +(inner.items[0].xauPrice / 31.1035).toFixed(2);
            source = 'goldprice.org';
          }
        }
      } catch(e) {}
    }

    // 最终 fallback：使用上次记录的价格或合理估算
    if (!pricePerGram || pricePerGram < 300 || pricePerGram > 2000) {
      // 如果有历史价格，用历史的
      if (goldLastSyncPrice > 300) {
        pricePerGram = goldLastSyncPrice;
        source = '上次缓存';
        if (!silent) showToast('⚠️ 网络受限，使用上次缓存金价');
      } else {
        // 使用合理的默认参考值（用户应手动更新）
        pricePerGram = 0;
        if (!silent) showToast('⚠️ 无法获取金价，请手动输入');
      }
    }

    if (pricePerGram > 0) {
      const prevPrice = goldPrice;
      goldPrice = pricePerGram;
      goldLastSyncTime = new Date().toLocaleString('zh-CN');
      goldLastSyncPrice = pricePerGram;
      save();
      renderGoldPage();
      renderHome();
      if (!silent) showToast(`✓ 金价已更新：¥${pricePerGram}/克`);
      else if (source && source !== '上次缓存') showToast(`金价已自动同步 ¥${pricePerGram}/克`);
      // 触发价格跳动动画
      const el = document.getElementById('goldPriceDisplay');
      if (el) { el.classList.add('price-updating'); setTimeout(()=>el.classList.remove('price-updating'),2000); }
    }
  } catch(e) {
    if (!silent) showToast('同步失败，请检查网络');
  }

  if (btn) { btn.disabled = false; btn.innerHTML = '🔄 同步金价'; }
}

/* ─────────────── FINANCE FUND SYNC ─────────────── */
function openFundSync(itemId) {
  const item = financeList.find(i => String(i.id) === String(itemId));
  if (!item) return;
  _fundSyncItemId = itemId;
  document.getElementById('fundSyncItemName').innerText = item.name + '  ·  本金 ' + fmtFull(item.principal);
  document.getElementById('fundSyncNewValue').value = item.currentValue || '';
  document.getElementById('fundSyncMask').classList.add('show');
  setTimeout(() => document.getElementById('fundSyncNewValue').focus(), 100);
}
document.getElementById('fundSyncOkBtn').onclick = () => {
  const val = parseFloat(document.getElementById('fundSyncNewValue').value);
  if (!val || val < 0) { showToast('请输入有效的当前价值'); return; }
  const idx = financeList.findIndex(i => String(i.id) === String(_fundSyncItemId));
  if (idx > -1) {
    financeList[idx].currentValue = val;
    financeList[idx].profit = +(val - financeList[idx].principal).toFixed(2);
    financeList[idx].lastSync = todayStr();
    save(); renderAll(); closeFundSync(); showToast('收益已更新 ✓');
  }
};
function closeFundSync() {
  _fundSyncItemId = null;
  document.getElementById('fundSyncMask').classList.remove('show');
}
document.getElementById('fundSyncMask').onclick = e => {
  if (e.target === document.getElementById('fundSyncMask')) closeFundSync();
};

function syncAllFunds() {
  // 批量打开提示：逐个引导用户更新
  const stale = financeList.filter(i => i.type === '基金' && i.lastSync !== todayStr());
  if (!stale.length) { showToast('✓ 所有基金今日已同步'); return; }
  // 打开第一个未同步的
  openFundSync(stale[0].id);
}

/* ─────────────── EXPIRE CHECK ─────────────── */
function checkExpireItems() {
  const now = new Date();
  const expireSoon = depositList.filter(item => {
    const days = (new Date(item.end) - now) / (1000*60*60*24);
    return days >= 0 && days <= 7;
  });
  renderExpireReminder(expireSoon);
  if (expireSoon.length > 0) showDesktopNotify(expireSoon);
}

function renderExpireReminder(list) {
  const el = document.getElementById('expireReminder');
  if (!list || !list.length) { el.innerHTML = ''; return; }
  el.innerHTML = `<div class="expire-strip">
    <div class="expire-strip-title">⏰ 定期即将到期</div>
    ${list.map(item => {
      const days = Math.ceil((new Date(item.end) - new Date()) / (1000*60*60*24));
      return `<div class="expire-item">
        <div><div class="expire-name">${esc(item.name)}</div><div class="expire-meta">到期日 ${item.end}</div></div>
        <div class="expire-val"><div class="expire-amt">${fmtFull(item.principal+item.interest)}</div>
        <div class="expire-days">${days===0?'今天到期':days+'天后到期'}</div></div>
      </div>`;
    }).join('')}</div>`;
}

function showDesktopNotify(list) {
  if (!("Notification" in window)) return;
  if (Notification.permission === "granted") {
    new Notification("小金库 · 定期到期提醒", { body: `你有 ${list.length} 笔定期即将到期` });
  } else if (Notification.permission !== "denied") {
    Notification.requestPermission();
  }
}

/* ─────────────── RENDER ALL ─────────────── */
function renderAll() { renderHome(); renderSaving(); renderDeposit(); renderFinance(); renderGoldPage(); checkExpireItems(); }

/* ─── HOME ─── */
function renderHome() {
  const totalSaving = savingList.reduce((a,b) => a + b.balance, 0);
  const totalDepositPrincipal = depositList.reduce((a,b) => a + b.principal, 0);
  const totalFinancePrincipal = financeList.reduce((a,b) => a + b.principal, 0);
  const totalGoldCost = goldList.reduce((a,b) => a + (b.costPrice * b.grams || 0), 0);
  const totalPrincipal = totalSaving + totalDepositPrincipal + totalFinancePrincipal + totalGoldCost;

  const totalDepositInterest = depositList.reduce((a,b) => a + b.interest, 0);
  const totalFinanceProfit = financeList.reduce((a,b) => a + b.profit, 0);
  
  // 黄金收益
  let totalGoldProfit = 0;
  goldList.forEach(g => {
    const mkt = goldPrice > 0 ? goldPrice * g.grams : (g.manualValue || g.costPrice * g.grams);
    const cost = (g.costPrice || goldPrice) * g.grams;
    totalGoldProfit += mkt - cost;
  });
  totalGoldProfit = +totalGoldProfit.toFixed(2);

  const totalAsset = totalPrincipal + totalFinanceProfit + Math.max(0, totalGoldProfit);

  document.getElementById('totalAsset').innerText = fmtFull(totalAsset);
  document.getElementById('totalDepositInterest').innerText = fmtFull(totalDepositInterest);
  document.getElementById('totalFinanceProfit').innerText = fmtFull(totalFinanceProfit);
  document.getElementById('totalGoldProfit').innerText = (totalGoldProfit >= 0 ? '+' : '') + fmtFull(totalGoldProfit);

  const ov = document.getElementById('homeOverview');
  const fpColor = totalFinanceProfit >= 0 ? 'var(--accent-s)' : '#EF4444';
  const gpColor = totalGoldProfit >= 0 ? '#D4A017' : '#EF4444';
  ov.innerHTML = `
    <div class="card" style="display:grid;grid-template-columns:1fr 1fr;gap:16px;cursor:default;background:#1A1A1A;color:#FFFFFF;">
      <div>
        <div style="font-size:11px;font-weight:700;color:rgba(255,255,255,.45);letter-spacing:.8px;margin-bottom:6px;">理财收益</div>
        <div style="font-size:22px;font-weight:800;color:${fpColor}">${totalFinanceProfit>=0?'+':''}${fmtFull(totalFinanceProfit)}</div>
      </div>
      <div>
        <div style="font-size:11px;font-weight:700;color:rgba(255,255,255,.45);letter-spacing:.8px;margin-bottom:6px;">活期日息</div>
        <div style="font-size:22px;font-weight:800;color:#34D399">+${fmtFull(savingList.reduce((a,b)=>a+b.dailyInterest,0))}</div>
      </div>
      <div>
        <div style="font-size:11px;font-weight:700;color:rgba(255,255,255,.45);letter-spacing:.8px;margin-bottom:6px;">黄金收益</div>
        <div style="font-size:18px;font-weight:700;color:${gpColor}">${totalGoldProfit>=0?'+':''}${fmtFull(totalGoldProfit)}</div>
      </div>
      <div>
        <div style="font-size:11px;font-weight:700;color:rgba(255,255,255,.45);letter-spacing:.8px;margin-bottom:6px;">定期到期利息</div>
        <div style="font-size:18px;font-weight:700;color:#FB923C">+${fmtFull(totalDepositInterest)}</div>
      </div>
    </div>`;
}

/* ─── SAVING ─── */
function renderSaving() {
  const c = document.getElementById('savingList');
  if (!savingList.length) {
    c.innerHTML = `<div class="empty"><div class="empty-icon">🌱</div>
      <div class="empty-text">还没有活期账户</div>
      <button class="empty-cta s" onclick="openModal('saving')">＋ 添加账户</button></div>`;
    return;
  }
  c.innerHTML = `<div class="card-list">${savingList.map(i => `
    <div class="card">
      <div class="card-top">
        <div class="card-name">${esc(i.name)}</div>
        <div class="card-amount" style="color:#34D399">${fmtFull(i.balance)}</div>
      </div>
      <div class="card-tags">
        <span class="tag accent-s">${esc(i.type)}</span>
        <span class="tag">年化 ${+i.rate}%</span>
        <span class="tag">日息 ${fmtFull(i.dailyInterest)}</span>
        ${i.note ? `<span class="tag">${esc(i.note)}</span>` : ''}
      </div>
      <div class="card-actions">
        <button class="act-btn edit-s" onclick="openModal('saving','${i.id}')">编辑</button>
        <button class="act-btn del" onclick="deleteItem('saving','${i.id}')">删除</button>
      </div>
    </div>`).join('')}</div>`;
}

/* ─── DEPOSIT ─── */
function renderDeposit() {
  const c = document.getElementById('depositList');
  if (!depositList.length) {
    c.innerHTML = `<div class="empty"><div class="empty-icon">💰</div>
      <div class="empty-text">还没有定期存款</div>
      <button class="empty-cta d" onclick="openModal('deposit')">＋ 添加存款</button></div>`;
    return;
  }
  c.innerHTML = `<div class="card-list">${depositList.map(i => {
    const r = remain(i.end);
    const statusClass = r < 0 ? 'over' : r <= 30 ? 'warn' : 'accent-d';
    const statusText = r < 0 ? '已到期' : r === 0 ? '今天到期' : `剩 ${r} 天`;
    return `<div class="card">
      <div class="card-top">
        <div class="card-name">${esc(i.name)}</div>
        <div class="card-amount" style="color:#FB923C">${fmtFull(i.principal+i.interest)}</div>
      </div>
      <div class="card-tags">
        <span class="tag ${statusClass}">${statusText}</span>
        <span class="tag">年化 ${+i.rate}%</span>
        <span class="tag">${+i.term} 个月</span>
        <span class="tag">利息 +${fmtFull(i.interest)}</span>
      </div>
      <div style="font-size:12px;color:var(--text-sub);margin-bottom:14px;">
        ${esc(i.start)} → ${esc(i.end)}
      </div>
      <div class="card-actions">
        <button class="act-btn edit-d" onclick="openModal('deposit','${i.id}')">编辑</button>
        <button class="act-btn del" onclick="deleteItem('deposit','${i.id}')">删除</button>
      </div>
    </div>`;
  }).join('')}</div>`;
}

/* ─── FINANCE ─── */
function renderFinance() {
  const c = document.getElementById('financeList');
  const strip = document.getElementById('financeSyncStrip');

  // 同步状态条
  const funds = financeList.filter(i => i.type === '基金');
  const staleCount = funds.filter(i => i.lastSync !== todayStr()).length;
  if (funds.length > 0) {
    strip.innerHTML = `<div class="sync-strip">
      <div class="sync-strip-left">
        <div class="sync-strip-title">📅 基金每日同步</div>
        <div class="sync-strip-sub">${staleCount > 0 ? `⚠️ ${staleCount} 个基金今日未更新收益` : '✓ 今日收益已全部更新'}</div>
      </div>
      ${staleCount > 0 ? `<button class="sync-all-btn" onclick="syncAllFunds()">去更新</button>` : ''}
    </div>`;
  } else {
    strip.innerHTML = '';
  }

  if (!financeList.length) {
    c.innerHTML = `<div class="empty"><div class="empty-icon">📈</div>
      <div class="empty-text">还没有理财产品</div>
      <button class="empty-cta f" onclick="openModal('finance')">＋ 添加理财</button></div>`;
    return;
  }
  c.innerHTML = `<div class="card-list">${financeList.map(i => {
    const rate = i.principal > 0 ? ((i.profit / i.principal) * 100).toFixed(2) : '0.00';
    const isPos = i.profit >= 0;
    const profitColor = isPos ? 'var(--accent-s)' : '#EF4444';
    const today = todayStr();
    const syncBadgeClass = !i.lastSync ? 'never' : i.lastSync === today ? 'today' : 'stale';
    const syncBadgeText = !i.lastSync ? '从未同步' : i.lastSync === today ? `今日已同步` : `上次 ${i.lastSync}`;
    const isFund = i.type === '基金';
    return `<div class="card">
      <div class="card-top">
        <div class="card-name">${esc(i.name)}</div>
        <div class="card-amount" style="color:${profitColor}">${isPos?'+':''}${fmtFull(i.profit)}</div>
      </div>
      <div class="card-tags">
        <span class="tag accent-f">${esc(i.type)}</span>
        <span class="tag">本金 ${fmtFull(i.principal)}</span>
        <span class="tag">现值 ${fmtFull(i.currentValue)}</span>
        <span class="tag" style="color:${profitColor};background:${isPos?'rgba(52,211,153,.1)':'rgba(239,68,68,.1)'}">${isPos?'+':''}${rate}%</span>
      </div>
      ${isFund ? `<div class="fund-sync-row">
        <span class="fund-sync-badge ${syncBadgeClass}">${syncBadgeText}</span>
        <div style="flex:1"></div>
        <button class="act-btn edit-f" onclick="openFundSync('${i.id}')" style="font-size:11px;padding:5px 12px;">📅 更新收益</button>
      </div>` : ''}
      <div class="card-actions" style="margin-top:${isFund?'8px':'0'}">
        <button class="act-btn edit-f" onclick="openModal('finance','${i.id}')">编辑</button>
        <button class="act-btn del" onclick="deleteItem('finance','${i.id}')">删除</button>
      </div>
    </div>`;
  }).join('')}</div>`;
}

/* ─── GOLD PAGE ─── */
function renderGoldPage() {
  // 金价面板
  const priceEl = document.getElementById('goldPriceDisplay');
  const changeEl = document.getElementById('goldChangeDisplay');
  if (priceEl) {
    if (goldPrice > 0) {
      priceEl.innerText = goldPrice.toFixed(2);
      // 显示涨跌
      if (goldLastSyncPrice && goldLastSyncPrice !== goldPrice) {
        const diff = goldPrice - goldLastSyncPrice;
        changeEl.style.display = 'inline-block';
        changeEl.className = 'gold-change ' + (diff >= 0 ? 'up' : 'down');
        changeEl.innerText = (diff >= 0 ? '+' : '') + diff.toFixed(2);
      }
    } else {
      priceEl.innerText = '-- ';
    }
  }
  const syncInfo = document.getElementById('goldLastSync');
  if (syncInfo) {
    syncInfo.innerText = goldLastSyncTime ? `上次同步：${goldLastSyncTime}` : '尚未同步金价';
  }

  // 持仓汇总
  const totalGrams = goldList.reduce((a,b) => a + b.grams, 0);
  const totalCost = goldList.reduce((a,b) => a + (b.costPrice||goldPrice) * b.grams, 0);
  let totalValue = 0;
  goldList.forEach(g => {
    if (g.isJD && goldPrice > 0) totalValue += goldPrice * g.grams;
    else if (g.manualValue) totalValue += g.manualValue;
    else if (goldPrice > 0) totalValue += goldPrice * g.grams;
    else totalValue += (g.costPrice || 0) * g.grams;
  });

  const totalGramsEl = document.getElementById('goldTotalGrams');
  const totalCostEl = document.getElementById('goldTotalCost');
  const totalValueEl = document.getElementById('goldTotalValue');
  if (totalGramsEl) totalGramsEl.innerText = totalGrams.toFixed(2) + 'g';
  if (totalCostEl) totalCostEl.innerText = fmt(totalCost);
  if (totalValueEl) totalValueEl.innerText = fmt(totalValue);

  // 京东积存金汇总卡
  const jdItems = goldList.filter(g => g.isJD);
  const jdSummary = document.getElementById('jdGoldSummary');
  if (jdItems.length > 0 && jdSummary) {
    const jdGrams = jdItems.reduce((a,b) => a + b.grams, 0);
    const jdCost = jdItems.reduce((a,b) => a + (b.costPrice||goldPrice)*b.grams, 0);
    const jdValue = goldPrice > 0 ? goldPrice * jdGrams : jdCost;
    const jdProfit = jdValue - jdCost;
    const jdProfitColor = jdProfit >= 0 ? '#059669' : '#DC2626';
    jdSummary.innerHTML = `<div class="jd-gold-card">
      <div class="jd-gold-header">
        <div class="jd-gold-title">🛒 京东积存金</div>
        <div class="jd-gold-badge">${goldPrice > 0 ? '实时同步' : '等待金价'}</div>
      </div>
      <div class="jd-holding-grid">
        <div class="jd-holding-item">
          <div class="jd-holding-label">持仓克重</div>
          <div class="jd-holding-val">${jdGrams.toFixed(2)}g</div>
        </div>
        <div class="jd-holding-item">
          <div class="jd-holding-label">当前市值</div>
          <div class="jd-holding-val">${goldPrice > 0 ? fmt(jdValue) : '待同步'}</div>
        </div>
        <div class="jd-holding-item">
          <div class="jd-holding-label">持仓成本</div>
          <div class="jd-holding-val">${fmt(jdCost)}</div>
        </div>
        <div class="jd-holding-item">
          <div class="jd-holding-label">浮动收益</div>
          <div class="jd-holding-val" style="color:${jdProfitColor}">${jdProfit>=0?'+':''}${fmt(jdProfit)}</div>
        </div>
      </div>
    </div>`;
  } else if (jdSummary) {
    jdSummary.innerHTML = '';
  }

  // 黄金持仓列表
  const c = document.getElementById('goldList');
  if (!goldList.length) {
    c.innerHTML = `<div class="empty"><div class="empty-icon">✦</div>
      <div class="empty-text">还没有黄金持仓</div>
      <button class="empty-cta g" onclick="openModal('gold')">＋ 添加黄金</button></div>`;
    return;
  }
  c.innerHTML = `<div class="card-list">${goldList.map(g => {
    const curVal = g.isJD && goldPrice > 0 ? goldPrice * g.grams
                 : g.manualValue ? g.manualValue
                 : goldPrice > 0 ? goldPrice * g.grams
                 : (g.costPrice || 0) * g.grams;
    const cost = (g.costPrice || goldPrice || 0) * g.grams;
    const profit = curVal - cost;
    const isPos = profit >= 0;
    const profitColor = isPos ? '#059669' : '#DC2626';
    const rate = cost > 0 ? ((profit / cost) * 100).toFixed(2) : '0.00';
    return `<div class="card">
      <div class="card-top">
        <div class="card-name">${esc(g.name)}${g.isJD ? ' 🛒' : ''}</div>
        <div class="card-amount" style="color:var(--accent-g)">${fmt(curVal)}</div>
      </div>
      <div class="card-tags">
        <span class="tag accent-g">${g.isJD ? '京东积存金' : '黄金'}</span>
        <span class="tag">${g.grams.toFixed(2)} 克</span>
        ${g.costPrice ? `<span class="tag">均价 ¥${g.costPrice}/g</span>` : ''}
        <span class="tag" style="color:${profitColor};background:${isPos?'rgba(52,211,153,.1)':'rgba(239,68,68,.1)'}">${isPos?'+':''}${rate}%</span>
      </div>
      ${g.isJD && goldPrice > 0 ? `<div style="font-size:11px;color:rgba(139,98,0,.5);margin-bottom:10px;">实时金价 ¥${goldPrice.toFixed(2)}/克 · 市值自动同步</div>` : ''}
      ${g.note ? `<div style="font-size:12px;color:var(--text-sub);margin-bottom:10px;">${esc(g.note)}</div>` : ''}
      <div class="card-actions">
        <div style="flex:1;font-size:13px;font-weight:700;color:${profitColor};align-self:center;">
          ${isPos?'+':''}${fmtFull(profit)}
        </div>
        <button class="act-btn edit-g" onclick="openModal('gold','${g.id}')">编辑</button>
        <button class="act-btn del" onclick="deleteItem('gold','${g.id}')">删除</button>
      </div>
    </div>`;
  }).join('')}</div>`;
}

/* ─────────────── TAB ─────────────── */
function bindTab() {
  document.querySelectorAll('.tab').forEach(tab => {
    tab.onclick = () => {
      document.querySelectorAll('.tab').forEach(i => i.classList.remove('active'));
      tab.classList.add('active');
      document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
      document.getElementById('page-' + tab.dataset.page).classList.add('active');
    };
  });
}

/* ─────────────── FORM TAB ─────────────── */
function bindFormTab() {
  document.querySelectorAll('.ftab').forEach(t => {
    t.onclick = () => switchFormType(t.dataset.type);
  });
}

const accentClass = { saving:'active-s', deposit:'active-d', finance:'active-f', gold:'active-g' };
function switchFormType(type) {
  document.querySelectorAll('.ftab').forEach(x => { x.className = 'ftab'; });
  document.querySelectorAll('.ftab').forEach(x => {
    if (x.dataset.type === type) x.classList.add(accentClass[type]);
  });
  document.querySelectorAll('.form-panel').forEach(p => p.classList.remove('active'));
  document.getElementById(type + 'Panel').classList.add('active');
  document.getElementById('formType').value = type;
  checkCurrentFormReady();
}

function checkCurrentFormReady() {
  const typ = document.getElementById('formType').value;
  if (typ === 'saving') checkSavingReady();
  else if (typ === 'deposit') checkDepositReady();
  else if (typ === 'finance') checkFinanceReady();
  else if (typ === 'gold') checkGoldReady();
}

/* ─────────────── SHEET CLOSE ─────────────── */
function bindSheetClose() {
  const mask = document.getElementById('modal');
  const sheet = document.getElementById('sheetContent');
  let startY = 0;
  mask.addEventListener('click', e => { if (e.target === mask) closeModal(); });
  sheet.addEventListener('touchstart', e => { startY = e.touches[0].clientY; }, {passive:true});
  sheet.addEventListener('touchend', e => {
    if (e.changedTouches[0].clientY - startY > 80) closeModal();
  }, {passive:true});
}
function closeModal() {
  document.getElementById('modal').classList.remove('show');
}

/* ─────────────── OPEN MODAL ─────────────── */
function openModal(type, id) {
  if (!['deposit','finance','saving','gold'].includes(type)) return;
  document.getElementById('editId').value = '';
  document.getElementById('sheetTitle').innerText = id ? '编辑' : '新增';
  switchFormType(type);

  if (id) {
    document.getElementById('editId').value = id;
    const list = type==='saving' ? savingList : type==='deposit' ? depositList : type==='finance' ? financeList : goldList;
    const item = list.find(i => String(i.id) === String(id));
    if (item) {
      if (type === 'saving') {
        document.getElementById('savingName').value = item.name;
        document.getElementById('savingBalance').value = item.balance;
        document.getElementById('savingRate').value = item.rate;
        document.getElementById('savingType').value = item.type;
        document.getElementById('savingNote').value = item.note || '';
      } else if (type === 'deposit') {
        document.getElementById('depositName').value = item.name;
        document.getElementById('depositAmount').value = item.principal;
        document.getElementById('depositRate').value = item.rate;
        document.getElementById('depositStartDate').value = item.start;
        document.getElementById('depositTerm').value = item.term;
      } else if (type === 'finance') {
        document.getElementById('financeName').value = item.name;
        document.getElementById('financeAmount').value = item.principal;
        document.getElementById('financeCurrentValue').value = item.currentValue;
        document.getElementById('financeType').value = item.type;
        document.getElementById('financeLastSync').value = item.lastSync || '';
      } else if (type === 'gold') {
        document.getElementById('goldName').value = item.name;
        document.getElementById('goldIsJD').value = item.isJD ? '1' : '0';
        document.getElementById('goldGrams').value = item.grams;
        document.getElementById('goldCostPrice').value = item.costPrice || '';
        document.getElementById('goldManualValue').value = item.manualValue || '';
        document.getElementById('goldNote').value = item.note || '';
        toggleJDGold();
      }
    }
  } else {
    if (type === 'saving') {
      document.getElementById('savingName').value = '';
      document.getElementById('savingBalance').value = '';
      document.getElementById('savingRate').value = '1.5';
      document.getElementById('savingType').selectedIndex = 0;
      document.getElementById('savingNote').value = '';
    } else if (type === 'deposit') {
      document.getElementById('depositName').value = '';
      document.getElementById('depositAmount').value = '';
      document.getElementById('depositRate').value = '2.5';
      document.getElementById('depositStartDate').valueAsDate = new Date();
      document.getElementById('depositTerm').value = '12';
    } else if (type === 'finance') {
      document.getElementById('financeName').value = '';
      document.getElementById('financeAmount').value = '';
      document.getElementById('financeCurrentValue').value = '';
      document.getElementById('financeType').selectedIndex = 0;
      document.getElementById('financeLastSync').value = '';
    } else if (type === 'gold') {
      document.getElementById('goldName').value = '';
      document.getElementById('goldIsJD').value = '0';
      document.getElementById('goldGrams').value = '';
      document.getElementById('goldCostPrice').value = '';
      document.getElementById('goldManualValue').value = '';
      document.getElementById('goldNote').value = '';
      toggleJDGold();
    }
  }
  document.getElementById('modal').classList.add('show');
  checkCurrentFormReady();
}

function toggleJDGold() {
  const isJD = document.getElementById('goldIsJD').value === '1';
  document.getElementById('goldManualValueGroup').style.display = isJD ? 'none' : 'block';
  // 京东积存金自动跟随金价，不需要手动输入价值
}

/* ─────────────── READY CHECK ─────────────── */
function checkSavingReady() {
  const name = document.getElementById('savingName').value.trim();
  const balance = document.getElementById('savingBalance').value;
  const ok = name && balance;
  const btn = document.querySelector('#savingPanel .submit-btn');
  btn.classList.toggle('ready', !!ok);
}
function checkDepositReady() {
  const name = document.getElementById('depositName').value.trim();
  const amount = document.getElementById('depositAmount').value;
  const start = document.getElementById('depositStartDate').value;
  const ok = name && amount && start;
  const btn = document.querySelector('#depositPanel .submit-btn');
  btn.classList.toggle('ready', !!ok);
}
function checkFinanceReady() {
  const name = document.getElementById('financeName').value.trim();
  const amount = document.getElementById('financeAmount').value;
  const current = document.getElementById('financeCurrentValue').value;
  const ok = name && amount && current;
  const btn = document.querySelector('#financePanel .submit-btn');
  btn.classList.toggle('ready', !!ok);
}
function checkGoldReady() {
  const name = document.getElementById('goldName').value.trim();
  const grams = document.getElementById('goldGrams').value;
  const ok = name && grams;
  const btn = document.querySelector('#goldPanel .submit-btn');
  btn.classList.toggle('ready', !!ok);
}

function bindSaveReady() {
  ['savingName','savingBalance'].forEach(id =>
    document.getElementById(id).addEventListener('input', checkSavingReady));
  ['depositName','depositAmount','depositStartDate'].forEach(id => {
    document.getElementById(id).addEventListener('input', checkDepositReady);
    document.getElementById(id).addEventListener('change', checkDepositReady);
  });
  ['financeName','financeAmount','financeCurrentValue'].forEach(id =>
    document.getElementById(id).addEventListener('input', checkFinanceReady));
  ['goldName','goldGrams'].forEach(id =>
    document.getElementById(id).addEventListener('input', checkGoldReady));
}

/* ─────────────── SUBMIT ─────────────── */
function submitForm() {
  const typ = document.getElementById('formType').value;
  const editId = document.getElementById('editId').value;

  if (typ === 'saving') {
    const name = document.getElementById('savingName').value.trim();
    const balance = parseFloat(document.getElementById('savingBalance').value) || 0;
    const rate = parseFloat(document.getElementById('savingRate').value) || 0;
    if (!name) { showToast('请填写账户名称'); return; }
    const dailyInterest = +(balance * rate / 100 / 365).toFixed(4);
    const item = { id: editId||Date.now(), name, balance, rate,
      type: document.getElementById('savingType').value,
      note: document.getElementById('savingNote').value.trim(), dailyInterest };
    upsert(savingList, item, editId);

  } else if (typ === 'deposit') {
    const name = document.getElementById('depositName').value.trim();
    const p = parseFloat(document.getElementById('depositAmount').value) || 0;
    const r = parseFloat(document.getElementById('depositRate').value) || 0;
    const s = document.getElementById('depositStartDate').value;
    const t = parseInt(document.getElementById('depositTerm').value) || 12;
    if (!name) { showToast('请填写名称'); return; }
    if (!s) { showToast('请选择开始日期'); return; }
    const end = new Date(s); end.setMonth(end.getMonth()+t);
    const endStr = end.toISOString().split('T')[0];
    const days = (end - new Date(s)) / 86400000;
    const interest = +(p * r / 100 * days / 365).toFixed(2);
    const item = { id: editId||Date.now(), name, principal:p, rate:r, start:s, term:t, end:endStr, interest };
    upsert(depositList, item, editId);

  } else if (typ === 'finance') {
    const name = document.getElementById('financeName').value.trim();
    const p = parseFloat(document.getElementById('financeAmount').value) || 0;
    const c = parseFloat(document.getElementById('financeCurrentValue').value) || 0;
    if (!name) { showToast('请填写名称'); return; }
    const lastSync = document.getElementById('financeLastSync').value || '';
    const item = { id: editId||Date.now(), name, principal:p, currentValue:c,
      type: document.getElementById('financeType').value,
      profit: +(c-p).toFixed(2), lastSync };
    upsert(financeList, item, editId);

  } else if (typ === 'gold') {
    const name = document.getElementById('goldName').value.trim();
    const grams = parseFloat(document.getElementById('goldGrams').value) || 0;
    const isJD = document.getElementById('goldIsJD').value === '1';
    const costPrice = parseFloat(document.getElementById('goldCostPrice').value) || goldPrice || 0;
    const manualValue = isJD ? null : (parseFloat(document.getElementById('goldManualValue').value) || null);
    const note = document.getElementById('goldNote').value.trim();
    if (!name) { showToast('请填写名称'); return; }
    if (!grams) { showToast('请填写克重'); return; }
    const item = { id: editId||Date.now(), name, grams, isJD, costPrice, manualValue, note };
    upsert(goldList, item, editId);
  }

  save(); renderAll(); closeModal(); showToast('已保存 ✓');
}

/* ─────────────── UPSERT / DELETE ─────────────── */
function upsert(list, item, editId) {
  if (editId) {
    const idx = list.findIndex(i => String(i.id) === String(editId));
    if (idx > -1) list.splice(idx, 1, item); else list.unshift(item);
  } else { list.unshift(item); }
}

function deleteItem(type, id) {
  if (!['deposit','finance','saving','gold'].includes(type)) return;
  const list = type==='deposit' ? depositList : type==='finance' ? financeList : type==='saving' ? savingList : goldList;
  const item = list.find(i => String(i.id) === String(id));
  _pendingDelete = { type, id };
  document.getElementById('confirmDesc').innerText = `「${item ? item.name : '该条目'}」删除后无法恢复`;
  document.getElementById('confirmMask').classList.add('show');
}
document.getElementById('confirmOkBtn').onclick = () => {
  if (!_pendingDelete) return;
  const { type, id } = _pendingDelete;
  if (type==='deposit') depositList = depositList.filter(i => String(i.id) !== String(id));
  else if (type==='finance') financeList = financeList.filter(i => String(i.id) !== String(id));
  else if (type==='saving') savingList = savingList.filter(i => String(i.id) !== String(id));
  else if (type==='gold') goldList = goldList.filter(i => String(i.id) !== String(id));
  _pendingDelete = null;
  save(); renderAll(); closeConfirm(); showToast('已删除');
};
function closeConfirm() {
  _pendingDelete = null;
  document.getElementById('confirmMask').classList.remove('show');
}
document.getElementById('confirmMask').onclick = e => {
  if (e.target === document.getElementById('confirmMask')) closeConfirm();
};

/* ─────────────── TOAST ─────────────── */
function showToast(msg) {
  let t = document.getElementById('_toast');
  if (!t) {
    t = document.createElement('div'); t.id = '_toast';
    Object.assign(t.style, {
      position:'fixed', bottom:'100px', left:'50%', transform:'translateX(-50%) translateY(10px)',
      background:'rgba(26,26,26,.9)', backdropFilter:'blur(16px)', WebkitBackdropFilter:'blur(16px)',
      border:'1px solid rgba(255,255,255,.1)',
      color:'#FFFFFF', padding:'10px 20px', borderRadius:'50px',
      fontSize:'13px', fontWeight:'600', zIndex:'9999',
      whiteSpace:'nowrap', transition:'opacity .25s,transform .25s', pointerEvents:'none',
      opacity:'0'
    });
    document.body.appendChild(t);
  }
  t.innerText = msg;
  t.style.opacity = '1'; t.style.transform = 'translateX(-50%) translateY(0)';
  clearTimeout(t._timer);
  t._timer = setTimeout(() => {
    t.style.opacity = '0'; t.style.transform = 'translateX(-50%) translateY(8px)';
  }, 2200);
}

/* ─────────────── UTILS ─────────────── */
function esc(str) {
  return String(str).replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;')
    .replace(/"/g,'&quot;').replace(/'/g,'&#39;');
}
function fmt(m) {
  const n = parseFloat(m || 0);
  if (Math.abs(n) >= 10000) return '¥' + (n/10000).toFixed(2) + 'w';
  return '¥' + n.toFixed(2).replace(/\B(?=(\d{3})+(?!\d))/g,',');
}
function fmtFull(m) {
  return '¥' + parseFloat(m||0).toFixed(2).replace(/\B(?=(\d{3})+(?!\d))/g,',');
}
function remain(end) {
  const d = new Date(end), now = new Date(); now.setHours(0,0,0,0);
  return Math.ceil((d - now) / 86400000);
}
</script>

</body>
</html>
