<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>전주 한옥마을 여행 여권</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif+KR:wght@400;600;700;900&family=Noto+Sans+KR:wght@400;500;700&display=swap" rel="stylesheet">
<style>
  :root{
    --paper:#F4EFE2;
    --paper-card:#FBF7EC;
    --ink:#2B2621;
    --ink-soft:#6b6255;
    --indigo:#2C3E63;
    --indigo-soft:#4a5c85;
    --stamp:#B23A28;
    --line:#d9cfb8;
    --gold:#C08A2E;
  }
  *{box-sizing:border-box;}
  body{
    margin:0;
    background:
      radial-gradient(ellipse at top left, rgba(44,62,99,0.05), transparent 50%),
      var(--paper);
    color:var(--ink);
    font-family:'Noto Sans KR',sans-serif;
    min-height:100vh;
  }
  ::selection{background:var(--indigo);color:#fff;}

  /* ---- Cover / Login ---- */
  #cover{
    min-height:100vh;
    display:flex;
    align-items:center;
    justify-content:center;
    padding:24px;
  }
  .passport{
    width:100%;
    max-width:420px;
    background:linear-gradient(160deg,var(--indigo) 0%, #1c2a45 100%);
    border-radius:14px;
    padding:48px 36px;
    box-shadow:0 30px 60px -20px rgba(28,42,69,0.5), 0 0 0 1px rgba(255,255,255,0.06) inset;
    text-align:center;
    color:#EDE7D6;
    position:relative;
    overflow:hidden;
  }
  .passport::before{
    content:"";
    position:absolute; inset:10px;
    border:1px solid rgba(237,231,214,0.25);
    border-radius:8px;
    pointer-events:none;
  }
  .emblem{
    width:64px;height:64px;margin:0 auto 18px;
    border:2px solid var(--gold);
    border-radius:50%;
    display:flex;align-items:center;justify-content:center;
    font-family:'Noto Serif KR',serif;
    font-size:26px;font-weight:900;color:var(--gold);
  }
  .passport h1{
    font-family:'Noto Serif KR',serif;
    font-weight:700;
    font-size:26px;
    letter-spacing:2px;
    margin:0 0 6px;
  }
  .passport .sub{
    font-size:12px;
    letter-spacing:4px;
    color:#B9C3DB;
    margin-bottom:34px;
  }
  .passport input{
    width:100%;
    padding:14px 16px;
    border-radius:8px;
    border:1px solid rgba(237,231,214,0.3);
    background:rgba(255,255,255,0.06);
    color:#fff;
    font-size:15px;
    margin-bottom:14px;
    outline:none;
  }
  .passport input::placeholder{color:#9aa5c2;}
  .passport input:focus{border-color:var(--gold);}
  .passport button{
    width:100%;
    padding:14px;
    border:none;
    border-radius:8px;
    background:var(--gold);
    color:#241a06;
    font-weight:700;
    font-size:15px;
    letter-spacing:1px;
    cursor:pointer;
    transition:transform .15s ease, filter .15s ease;
  }
  .passport button:hover{filter:brightness(1.08); transform:translateY(-1px);}
  .passport .note{font-size:11px;color:#8b94b3;margin-top:16px;line-height:1.6;}

  /* ---- Main ---- */
  #app{display:none; max-width:900px; margin:0 auto; padding:28px 18px 80px;}
  header.top{
    display:flex; justify-content:space-between; align-items:flex-start;
    margin-bottom:22px; gap:12px; flex-wrap:wrap;
  }
  header.top h1{
    font-family:'Noto Serif KR',serif;
    font-size:24px; margin:0 0 4px;
  }
  header.top .who{font-size:13px; color:var(--ink-soft);}
  .logout{
    font-size:12px; color:var(--indigo); background:none; border:1px solid var(--line);
    padding:8px 14px; border-radius:20px; cursor:pointer;
  }
  .admin-link{font-size:12px;color:var(--ink-soft);text-decoration:underline;cursor:pointer;background:none;border:none;padding:0;}

  .tabs{display:flex; gap:10px; margin:20px 0 18px;}
  .tab{
    flex:1;
    text-align:center;
    padding:14px 10px;
    border-radius:10px;
    border:1px solid var(--line);
    background:var(--paper-card);
    cursor:pointer;
    position:relative;
  }
  .tab .zone-label{font-size:11px; letter-spacing:2px; color:var(--ink-soft);}
  .tab .zone-name{font-family:'Noto Serif KR',serif; font-weight:700; font-size:16px; margin-top:2px;}
  .tab .zone-count{font-size:12px;color:var(--indigo); margin-top:4px;}
  .tab.active{border-color:var(--indigo); background:#fff; box-shadow:0 6px 16px -8px rgba(44,62,99,0.35);}
  .tab.active .zone-name{color:var(--indigo);}

  .progress-bar{
    height:8px; background:var(--line); border-radius:4px; overflow:hidden; margin-bottom:6px;
  }
  .progress-bar > div{height:100%; background:linear-gradient(90deg,var(--indigo),var(--indigo-soft)); transition:width .4s ease;}
  .progress-text{font-size:12px; color:var(--ink-soft); margin-bottom:20px; display:flex; justify-content:space-between;}
  .gift-hint{color:var(--stamp); font-weight:700;}

  .grid{display:grid; grid-template-columns:repeat(auto-fill,minmax(230px,1fr)); gap:16px;}
  .card{
    background:var(--paper-card);
    border:1px solid var(--line);
    border-radius:12px;
    overflow:hidden;
    display:flex; flex-direction:column;
    position:relative;
  }
  .card .num{
    position:absolute; top:10px; left:10px;
    font-family:'Noto Serif KR',serif; font-weight:700; font-size:12px;
    background:var(--indigo); color:#fff; width:24px;height:24px;border-radius:50%;
    display:flex;align-items:center;justify-content:center; z-index:2;
  }
  .photo-zone{
    height:150px; background:#e9e2cd;
    display:flex;align-items:center;justify-content:center;
    position:relative; overflow:hidden;
    cursor:pointer;
  }
  .photo-zone img{width:100%;height:100%;object-fit:cover;}
  .photo-zone .placeholder{font-size:12px; color:var(--ink-soft); text-align:center; padding:0 10px;}
  .stamp{
    position:absolute; width:76px; height:76px; z-index:3;
    border:3px solid var(--stamp);
    border-radius:50%;
    color:var(--stamp);
    display:flex;align-items:center;justify-content:center;
    font-family:'Noto Serif KR',serif; font-weight:900; font-size:12px;
    transform:rotate(-16deg);
    background:rgba(255,255,255,0.15);
    mix-blend-mode:multiply;
    text-align:center;
    line-height:1.2;
    animation:stampIn .35s cubic-bezier(.2,1.4,.5,1);
  }
  @keyframes stampIn{from{transform:rotate(-16deg) scale(2.4); opacity:0;} to{transform:rotate(-16deg) scale(1); opacity:1;}}
  .card-body{padding:12px 14px 14px;}
  .card-body .name{font-weight:700; font-size:14px; margin-bottom:3px;}
  .card-body .desc{font-size:12px; color:var(--ink-soft); line-height:1.5; min-height:32px;}
  .card-body .status{font-size:11px; margin-top:8px; font-weight:700;}
  .status.done{color:var(--indigo);}
  .status.todo{color:var(--ink-soft);}
  input[type=file]{display:none;}

  /* Modal */
  .overlay{
    position:fixed; inset:0; background:rgba(20,15,8,0.55);
    display:none; align-items:center; justify-content:center; z-index:50; padding:20px;
  }
  .overlay.show{display:flex;}
  .modal{
    background:var(--paper-card); border-radius:14px; max-width:380px; width:100%;
    padding:32px 26px; text-align:center; position:relative;
    box-shadow:0 30px 60px -20px rgba(0,0,0,0.4);
  }
  .modal .ring{
    width:64px;height:64px;border-radius:50%; margin:0 auto 16px;
    background:var(--stamp); color:#fff; display:flex;align-items:center;justify-content:center;
    font-size:28px;
  }
  .modal h2{font-family:'Noto Serif KR',serif; font-size:20px; margin:0 0 8px;}
  .modal p{font-size:13px; color:var(--ink-soft); line-height:1.6; margin-bottom:18px;}
  .code-box{
    background:var(--paper); border:1px dashed var(--gold); border-radius:8px;
    padding:14px; font-family:'Noto Serif KR',serif; font-weight:700; font-size:18px;
    letter-spacing:3px; color:var(--gold); margin-bottom:18px;
  }
  .modal button{
    width:100%; padding:13px; border:none; border-radius:8px; background:var(--indigo);
    color:#fff; font-weight:700; cursor:pointer; font-size:14px;
  }

  /* Admin */
  #admin{display:none; max-width:700px; margin:0 auto; padding:28px 18px 80px;}
  #admin h1{font-family:'Noto Serif KR',serif;}
  .log-row{display:flex; justify-content:space-between; gap:10px; padding:12px 14px; border:1px solid var(--line); border-radius:8px; background:var(--paper-card); margin-bottom:8px; font-size:13px; flex-wrap:wrap;}
  .log-row .code{color:var(--gold); font-weight:700;}
  .back{background:none;border:1px solid var(--line);padding:8px 14px;border-radius:20px;font-size:12px;cursor:pointer;margin-bottom:20px;}

  @media (max-width:480px){
    .passport{padding:38px 24px;}
  }
</style>
</head>
<body>

<!-- COVER / LOGIN -->
<div id="cover">
  <div class="passport">
    <div class="emblem">全</div>
    <h1>전주 한옥마을<br>여행 여권</h1>
    <div class="sub">JEONJU HANOK VILLAGE QUEST</div>
    <input id="emailInput" type="email" placeholder="이메일을 입력해줘">
    <button onclick="login()">여권 발급받기</button>
    <div class="note">완료한 퀘스트는 이 이메일로 저장돼.<br>같은 이메일로 다시 들어오면 이어서 할 수 있어.</div>
  </div>
</div>

<!-- MAIN APP -->
<div id="app">
  <header class="top">
    <div>
      <h1>전주 한옥마을 여행 여권</h1>
      <div class="who" id="whoLabel"></div>
    </div>
    <div style="display:flex; flex-direction:column; align-items:flex-end; gap:8px;">
      <button class="logout" onclick="logout()">로그아웃</button>
      <button class="admin-link" onclick="showAdmin()">관리자 보기</button>
    </div>
  </header>

  <div class="tabs">
    <div class="tab active" id="tabBtn0" onclick="switchZone(0)">
      <div class="zone-label">ZONE 01</div>
      <div class="zone-name">중심 구역</div>
      <div class="zone-count" id="tabCount0">0 / 10</div>
    </div>
    <div class="tab" id="tabBtn1" onclick="switchZone(1)">
      <div class="zone-label">ZONE 02</div>
      <div class="zone-name">외곽 구역</div>
      <div class="zone-count" id="tabCount1">0 / 10</div>
    </div>
  </div>

  <div class="progress-bar"><div id="progFill" style="width:0%"></div></div>
  <div class="progress-text">
    <span id="progText">0 / 10 완료</span>
    <span class="gift-hint" id="giftHint">3개 달성 시 선물 코드 발급!</span>
  </div>

  <div class="grid" id="grid"></div>
</div>

<!-- ADMIN -->
<div id="admin">
  <button class="back" onclick="hideAdmin()">← 돌아가기</button>
  <h1>선물 발급 기록 (관리자용)</h1>
  <p style="font-size:13px;color:var(--ink-soft);margin-bottom:20px;">
    아래 목록은 모든 사용자에게 공유되는 기록이야. 실제 이메일 발송은 이 목록을 보고 수동으로 하거나,
    Google Apps Script / Zapier 같은 외부 서비스와 연동해서 자동화할 수 있어.
  </p>
  <div id="logList"></div>
</div>

<!-- GIFT MODAL -->
<div class="overlay" id="giftOverlay">
  <div class="modal">
    <div class="ring">🎁</div>
    <h2>선물 코드가 발급됐어!</h2>
    <p id="giftMsg">구역 퀘스트 3개를 완료했어. 아래 코드를 보여주면 선물을 받을 수 있어.</p>
    <div class="code-box" id="giftCode">------</div>
    <button onclick="closeGift()">확인</button>
  </div>
</div>

<script>
// ---------- Quest Data ----------
const ZONES = [
  {
    name: "중심 구역",
    quests: [
      {name:"경기전", desc:"태조 어진을 모신 조선 왕실의 성지"},
      {name:"전동성당", desc:"붉은 벽돌이 아름다운 근대 건축물"},
      {name:"풍남문", desc:"전주읍성의 남쪽 관문"},
      {name:"오목대", desc:"이성계가 회군길에 오른 언덕"},
      {name:"전주향교", desc:"은행나무가 우거진 조선시대 교육기관"},
      {name:"최명희문학관", desc:"소설 혼불의 산실"},
      {name:"한벽루", desc:"전주천이 내려다보이는 정자"},
      {name:"남부시장", desc:"청년몰이 있는 전통 시장"},
      {name:"자만벽화마을", desc:"골목마다 그림이 가득한 마을"},
      {name:"전주공예품전시관", desc:"전주 전통 공예의 모든 것"},
    ]
  },
  {
    name: "외곽 구역",
    quests: [
      {name:"덕진공원 연못", desc:"연꽃으로 유명한 도심 속 공원"},
      {name:"국립무형유산원", desc:"무형문화유산을 체험하는 공간"},
      {name:"전주한옥생활체험관", desc:"한옥 생활을 직접 체험"},
      {name:"완판본문화관", desc:"조선시대 출판문화의 중심지"},
      {name:"서학동예술마을", desc:"작은 갤러리가 모인 예술촌"},
      {name:"전주천 상류", desc:"맑은 물이 흐르는 산책로"},
      {name:"다가공원", desc:"전주천변의 오래된 공원"},
      {name:"전주역사박물관", desc:"전주의 역사를 한눈에"},
      {name:"전주부성 성벽길", desc:"옛 읍성의 흔적을 따라 걷는 길"},
      {name:"전주 야시장 거리", desc:"밤이 되면 살아나는 먹거리 골목"},
    ]
  }
];
const GOAL = 3;

// ---------- State ----------
let email = null;
let currentZone = 0;
let state = null; // {zones:[[bool*10],[bool*10]], photos:[[b64*10],[b64*10]], giftClaimed:[bool,bool], giftCodes:[str,str]}

function emptyState(){
  return {
    zones:[Array(10).fill(false), Array(10).fill(false)],
    photos:[Array(10).fill(null), Array(10).fill(null)],
    giftClaimed:[false,false],
    giftCodes:[null,null]
  };
}

function storageKey(e){ return "progress:" + e.trim().toLowerCase(); }

async function login(){
  const val = document.getElementById('emailInput').value.trim();
  if(!val || !val.includes('@')){ alert('올바른 이메일을 입력해줘'); return; }
  email = val.toLowerCase();
  try{
    const res = await window.storage.get(storageKey(email));
    state = res ? JSON.parse(res.value) : emptyState();
  }catch(e){
    state = emptyState();
  }
  document.getElementById('cover').style.display = 'none';
  document.getElementById('app').style.display = 'block';
  document.getElementById('whoLabel').textContent = email;
  renderZone();
}

function logout(){
  email = null; state = null;
  document.getElementById('app').style.display = 'none';
  document.getElementById('admin').style.display = 'none';
  document.getElementById('cover').style.display = 'flex';
  document.getElementById('emailInput').value = '';
}

async function saveState(){
  try{
    await window.storage.set(storageKey(email), JSON.stringify(state));
  }catch(e){
    console.error('저장 실패', e);
  }
}

function switchZone(i){
  currentZone = i;
  document.getElementById('tabBtn0').classList.toggle('active', i===0);
  document.getElementById('tabBtn1').classList.toggle('active', i===1);
  renderZone();
}

function renderZone(){
  const zone = ZONES[currentZone];
  const done = zone.quests.filter((_,i)=>state.zones[currentZone][i]).length;

  document.getElementById('tabCount0').textContent = state.zones[0].filter(Boolean).length + " / 10";
  document.getElementById('tabCount1').textContent = state.zones[1].filter(Boolean).length + " / 10";
  document.getElementById('progFill').style.width = (done/10*100)+'%';
  document.getElementById('progText').textContent = done + " / 10 완료";
  document.getElementById('giftHint').textContent = done >= GOAL
    ? (state.giftClaimed[currentZone] ? "선물 코드 발급 완료 ✓" : "선물 코드 발급 가능!")
    : (GOAL - done) + "개 더 하면 선물 코드!";

  const grid = document.getElementById('grid');
  grid.innerHTML = '';
  zone.quests.forEach((q,i)=>{
    const isDone = state.zones[currentZone][i];
    const photo = state.photos[currentZone][i];
    const card = document.createElement('div');
    card.className = 'card';
    card.innerHTML = `
      <div class="num">${i+1}</div>
      <div class="photo-zone" onclick="triggerUpload(${i})">
        ${photo ? `<img src="${photo}">` : `<div class="placeholder">📷 탭해서 사진 올리기</div>`}
        ${isDone ? `<div class="stamp">완료<br>STAMP</div>` : ''}
      </div>
      <div class="card-body">
        <div class="name">${q.name}</div>
        <div class="desc">${q.desc}</div>
        <div class="status ${isDone?'done':'todo'}">${isDone ? '✓ 퀘스트 완료' : '사진을 찍어서 인증해줘'}</div>
      </div>
      <input type="file" accept="image/*" capture="environment" id="file-${i}" onchange="handleFile(${i}, this)">
    `;
    grid.appendChild(card);
  });
}

function triggerUpload(i){
  document.getElementById('file-'+i).click();
}

function handleFile(i, input){
  const file = input.files[0];
  if(!file) return;
  const reader = new FileReader();
  reader.onload = function(e){
    const img = new Image();
    img.onload = function(){
      // resize to keep storage small
      const maxW = 480;
      const scale = Math.min(1, maxW/img.width);
      const canvas = document.createElement('canvas');
      canvas.width = img.width*scale;
      canvas.height = img.height*scale;
      const ctx = canvas.getContext('2d');
      ctx.drawImage(img,0,0,canvas.width,canvas.height);
      const dataUrl = canvas.toDataURL('image/jpeg', 0.7);
      completeQuest(i, dataUrl);
    };
    img.src = e.target.result;
  };
  reader.readAsDataURL(file);
}

async function completeQuest(i, dataUrl){
  state.photos[currentZone][i] = dataUrl;
  const wasDone = state.zones[currentZone][i];
  state.zones[currentZone][i] = true;
  await saveState();
  renderZone();

  const doneCount = state.zones[currentZone].filter(Boolean).length;
  if(!wasDone && doneCount >= GOAL && !state.giftClaimed[currentZone]){
    await claimGift(currentZone);
  }
}

async function claimGift(zoneIdx){
  const code = genCode();
  state.giftClaimed[zoneIdx] = true;
  state.giftCodes[zoneIdx] = code;
  await saveState();

  // shared admin log
  try{
    const logKey = "giftlog:" + Date.now() + "-" + Math.random().toString(36).slice(2,7);
    await window.storage.set(logKey, JSON.stringify({
      email, zone: ZONES[zoneIdx].name, code, date: new Date().toISOString()
    }), true);
  }catch(e){ console.error(e); }

  document.getElementById('giftMsg').textContent =
    `${ZONES[zoneIdx].name} 퀘스트 3개를 완료했어! 아래 코드를 보여주면 선물을 받을 수 있어.`;
  document.getElementById('giftCode').textContent = code;
  document.getElementById('giftOverlay').classList.add('show');
  renderZone();
}

function closeGift(){
  document.getElementById('giftOverlay').classList.remove('show');
}

function genCode(){
  const chars = 'ABCDEFGHJKLMNPQRSTUVWXYZ23456789';
  let c = '';
  for(let i=0;i<6;i++) c += chars[Math.floor(Math.random()*chars.length)];
  return c;
}

// ---------- Admin view ----------
async function showAdmin(){
  document.getElementById('app').style.display = 'none';
  document.getElementById('admin').style.display = 'block';
  const listEl = document.getElementById('logList');
  listEl.innerHTML = '불러오는 중...';
  try{
    const keys = await window.storage.list('giftlog:', true);
    if(!keys || !keys.keys || keys.keys.length===0){
      listEl.innerHTML = '<p style="font-size:13px;color:var(--ink-soft);">아직 발급된 선물 코드가 없어.</p>';
      return;
    }
    const rows = [];
    for(const k of keys.keys){
      try{
        const r = await window.storage.get(k, true);
        if(r) rows.push(JSON.parse(r.value));
      }catch(e){}
    }
    rows.sort((a,b)=> new Date(b.date) - new Date(a.date));
    listEl.innerHTML = rows.map(r => `
      <div class="log-row">
        <span>${r.email}</span>
        <span>${r.zone}</span>
        <span class="code">${r.code}</span>
        <span>${new Date(r.date).toLocaleString('ko-KR')}</span>
      </div>
    `).join('');
  }catch(e){
    listEl.innerHTML = '<p style="font-size:13px;color:var(--ink-soft);">기록을 불러오지 못했어.</p>';
  }
}

function hideAdmin(){
  document.getElementById('admin').style.display = 'none';
  document.getElementById('app').style.display = 'block';
}
</script>
</body>
</html>
