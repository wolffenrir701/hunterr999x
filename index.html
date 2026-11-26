<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HUNTER 999x - Tibia Like | Vocações + Coins</title>
<style>
*{box-sizing:border-box;font-family:Arial,sans-serif} body{background:#0f0f1a;color:#fff;margin:0;padding:12px;max-width:560px;margin:auto}
.top{display:flex;justify-content:space-between;background:#1e1e30;padding:12px;border-radius:12px}
.bar{height:14px;background:#333;border-radius:99px;overflow:hidden;margin:4px 0} .fill{height:100%;background:linear-gradient(90deg,#00ff88,#00ccff);width:0%;transition:.3s} .hp{background:#ff4444!important} .mana{background:#4488ff!important}
.card{background:#1e1e30;padding:14px;border-radius:14px;margin-top:12px;text-align:center}
.monster{font-size:90px;margin:8px 0;cursor:pointer} .monster:active{transform:scale(.92)}
button{width:100%;padding:13px;border:0;border-radius:10px;font-weight:900;font-size:15px;margin-top:8px;cursor:pointer}
.hunt{background:#00ff88} .skill{background:#a855f7;color:#fff} .potion{background:#ffaa00} .boss{background:#ff4444;color:#fff}
.log{background:#0008;padding:10px;height:150px;overflow-y:auto;text-align:left;font-size:13px;border-radius:10px;margin-top:10px}
.loot{display:flex;gap:6px;flex-wrap:wrap;justify-content:center;margin-top:8px} .item{background:#2a2a45;padding:6px 10px;border-radius:99px;font-size:13px;border:1px solid #444}
.stats{display:grid;grid-template-columns:1fr 1fr 1fr 1fr;gap:8px;margin-top:12px} .stat{background:#2a2a45;padding:10px;border-radius:10px} .stat b{font-size:18px;display:block}
.maps{display:grid;grid-template-columns:1fr 1fr 1fr;gap:8px} .map{padding:10px;border-radius:10px;background:#2a2a45;cursor:pointer;border:2px solid transparent} .map.active{border-color:#00ff88;background:#00ff8833}
.vocs{display:grid;grid-template-columns:1fr 1fr;gap:8px} .voc{padding:12px;border-radius:10px;background:#2a2a45;cursor:pointer;border:2px solid transparent;text-align:left} .voc.active{border-color:#ffd700;background:#ffd70022} .voc small{color:#aaa;display:block;font-size:11px}
input{width:100%;padding:12px;border-radius:10px;border:0;margin-top:8px;background:#2a2a45;color:#fff}
.badge{background:#ffd700;color:#000;padding:2px 8px;border-radius:99px;font-size:11px;font-weight:900}
.boost{background:#ffd70022;border:1px solid #ffd700;padding:8px;border-radius:10px;margin-top:8px;font-size:13px}
</style>
</head>
<body>
<div class="top"><div><b>⚔️ HUNTER 999x v3</b><br><small>Vocações + Coins + Boost</small></div><div style="text-align:right">Level <b id="level" style="font-size:24px;color:#00ff88">1</b><br><span id="vocName">Knight</span> <span class="badge" id="outfitBadge">No Outfit</span></div></div>

<div class="card"><b>👤 SEU CHAR</b><input id="playerName" placeholder="Nome do char" maxlength="12" onchange="save()"><div style="display:flex;justify-content:space-between;margin-top:8px"><span>HP <span id="hpText"></span></span><span>MANA <span id="manaText"></span></span></div><div class="bar"><div class="fill hp" id="hpBar"></div></div><div class="bar"><div class="fill mana" id="manaBar"></div></div><div class="bar"><div class="fill" id="xpBar"></div></div><div id="xpText" style="font-size:12px;color:#aaa"></div><div id="boostInfo" class="boost">🚀 Sem Boost ativo</div></div>

<div class="stats"><div class="stat"><small>💰 GOLD</small><b id="gold">0</b></div><div class="stat"><small>🪙 TIBIA COINS</small><b id="tc" style="color:#ffd700">0</b></div><div class="stat"><small>🗡️ DANO</small><b id="dmg">10</b></div><div class="stat"><small>🧪 POTION</small><b id="pot">3</b></div></div>

<div class="card" style="text-align:left"><b>🧙 ESCOLHA SUA VOCAÇÃO</b><div class="vocs" style="margin-top:8px">
<div class="voc active" id="voc-Knight" onclick="setVoc('Knight')">⚔️ KNIGHT<small>Tank | HP alto<br>Skill: Exori - Dano em área<br>Passiva: +50% HP</small></div>
<div class="voc" id="voc-Mage" onclick="setVoc('Mage')">🔥 MAGE<small>Dano mágico gigante<br>Skill: Exori Flam - 3x Dano<br>Passiva: +100% Mana</small></div>
<div class="voc" id="voc-Druid" onclick="setVoc('Druid')">🌿 DRUID<small>Healer<br>Skill: Exura Vita - Cura 100%<br>Passiva: Regen HP</small></div>
<div class="voc" id="voc-Paladin" onclick="setVoc('Paladin')">🏹 PALADIN<small>Distância / Crítico<br>Skill: Exori San - Crítico 50%<br>Passiva: +30% Gold</small></div>
<div class="voc" id="voc-Monk" onclick="setVoc('Monk')">🥋 MONK<small>Combo / Roubo de vida<br>Skill: Exori Fist - 5 hits + rouba HP<br>Passiva: +20% Lifesteal</small></div>
</div><small style="color:#888">Trocar de vocação reseta só o bônus, mantém level.</small></div>

<div class="card"><b>🗺️ HUNT</b><div class="maps" style="margin-top:8px"><div class="map active" id="map-floresta" onclick="changeMap('floresta')">🌲 Floresta<small>Lvl 1-30</small></div><div class="map" id="map-caverna" onclick="changeMap('caverna')">🪨 Caverna<small>Lvl 30-80<br>2x Gold</small></div><div class="map" id="map-inferno" onclick="changeMap('inferno')">🔥 Inferno<small>Lvl 80+<br>4x Drop</small></div></div></div>

<div class="card"><div id="monsterName" style="font-weight:900"></div><div class="monster" id="monster" onclick="attack()">🐀</div><div>HP Monstro: <b id="mHp"></b> / <span id="mMax"></span></div><div class="bar"><div class="fill hp" id="mBar"></div></div><button class="hunt" onclick="attack()">⚔️ ATACAR</button><button class="skill" id="skillBtn" onclick="useSkill()">✨ USAR SKILL DA VOCAÇÃO</button><button class="potion" onclick="usePotion()">🧪 POTION (+50 HP)</button><button class="boss" onclick="spawnBoss()">👹 BOSS (Loot 4x)</button><div class="loot" id="loot"></div></div>

<div class="card" style="text-align:left"><b>🪙 STORE - TIBIA COINS (Igual Global)</b><div style="font-size:13px;color:#aaa;margin-top:6px">1 TC = 100 Gold | Troque Gold por TC e compre itens premium</div><button onclick="buyTC(10)" style="background:#ffd700">🪙 COMPRAR 10 TC - 1000 Gold</button><button onclick="buyTC(50)" style="background:#ffd700">🪙 COMPRAR 50 TC - 4500 Gold (10% OFF)</button><button onclick="buyStore('xpboost')" style="background:#00ccff">🚀 XP BOOST 2x por 5 min - 20 TC</button><button onclick="buyStore('lootboost')" style="background:#00ff88">📦 LOOT BOOST 2x por 5 min - 20 TC</button><button onclick="buyStore('outfit')" style="background:#a855f7;color:#fff">👑 OUTFIT PREMIUM - 30 TC</button><button onclick="buyStore('mount')" style="background:#ff6b00;color:#fff">🐎 MOUNT - 30 TC (+10% Velocidade)</button><button onclick="buyStore('hp')" style="background:#ff5555">❤️ +50 HP MÁX - 150 Gold</button></div>

<div class="card" style="text-align:left"><b>🏆 RANKING</b><div id="ranking"></div></div>
<div class="log" id="log"></div>

<script>
let S = JSON.parse(localStorage.getItem('hunter_v3')||'{}');
let level=S.level||1, xp=S.xp||0, xpNeed=S.xpNeed||100, gold=S.gold||0, tc=S.tc||0, dmg=S.dmg||10, pot=S.pot||3, maxHp=S.maxHp||100, hp=maxHp, maxMana=S.maxMana||100, mana=maxMana, voc=S.voc||'Knight', currentMap=S.map||'floresta', outfit=S.outfit||'', mount=S.mount||false, boostXpUntil=0, boostLootUntil=0;
document.getElementById('playerName').value=S.name||'';
let mHp=50,mMax=50,mLevel=1,isBoss=false, skillCd=0;
let vocs={
 Knight:{skill:'Exori', desc:'Dano em área', hpMult:1.5, manaMult:1, dmgMult:1},
 Mage:{skill:'Exori Flam', desc:'3x Dano Mágico', hpMult:0.8, manaMult:2, dmgMult:1.4},
 Druid:{skill:'Exura Vita', desc:'Cura 100%', hpMult:1.1, manaMult:1.5, dmgMult:0.9},
 Paladin:{skill:'Exori San', desc:'Crítico 50%', hpMult:1.1, manaMult:1.1, dmgMult:1.2},
 Monk:{skill:'Exori Fist', desc:'5 hits + Lifesteal', hpMult:1.2, manaMult:1.2, dmgMult:1.1}
};
let maps={floresta:{list:[{e:'🐀',n:'Rat'},{e:'🐍',n:'Snake'},{e:'🐺',n:'Wolf'}],g:1,x:1},caverna:{list:[{e:'💀',n:'Skeleton'},{e:'🧟',n:'Zombie'},{e:'🕷️',n:'Spider'}],g:2,x:1.5},inferno:{list:[{e:'🐉',n:'Dragon'},{e:'👹',n:'Demon'},{e:'🧛',n:'Vampire'}],g:4,x:2.5}};
let loots=['⚔️ Sword','🛡️ Shield','💎 Gem','🧪 Potion','👑 Crown','💰 Gold','🔮 Stone','🍖 Meat'];
function save(){ localStorage.setItem('hunter_v3', JSON.stringify({level,xp,xpNeed,gold,tc,dmg,pot,maxHp,maxMana,voc,map:currentMap,name:document.getElementById('playerName').value,outfit,mount})); updateRank(); }
function log(t){ document.getElementById('log').innerHTML=t+'<br>'+document.getElementById('log').innerHTML; }
function getBoost(){ let now=Date.now(); let xpB=now<boostXpUntil?2:1; let lootB=now<boostLootUntil?2:1; return {xpB,lootB}; }
function update(){
 let v=vocs[voc]; document.getElementById('level').innerText=level; document.getElementById('vocName').innerText=voc.toUpperCase(); document.getElementById('outfitBadge').innerText=outfit?outfit:'No Outfit';
 document.getElementById('hpText').innerText=hp+'/'+maxHp; document.getElementById('manaText').innerText=mana+'/'+maxMana;
 document.getElementById('hpBar').style.width=(hp/maxHp*100)+'%'; document.getElementById('manaBar').style.width=(mana/maxMana*100)+'%'; document.getElementById('xpBar').style.width=(xp/xpNeed*100)+'%';
 document.getElementById('xpText').innerText=xp+' / '+xpNeed+' XP'; document.getElementById('gold').innerText=gold; document.getElementById('tc').innerText=tc; document.getElementById('dmg').innerText=dmg; document.getElementById('pot').innerText=pot;
 document.getElementById('mHp').innerText=Math.max(0,mHp); document.getElementById('mMax').innerText=mMax; document.getElementById('mBar').style.width=(mHp/mMax*100)+'%';
 document.getElementById('skillBtn').innerText='✨ '+v.skill+' - '+v.desc+' (Cooldown '+skillCd+'s)';
 let b=getBoost(); document.getElementById('boostInfo').innerText=(b.xpB>1?'🚀 XP BOOST 2x ATIVO! ':'')+(b.lootB>1?'📦 LOOT BOOST 2x ATIVO! ':'')+(b.xpB==1&&b.lootB==1?'🚀 Sem Boost ativo':'');
 document.querySelectorAll('.voc').forEach(e=>e.classList.remove('active')); let el=document.getElementById('voc-'+voc); if(el) el.classList.add('active');
 save();
}
function setVoc(v){ voc=v; let baseHp=100+ (level-1)*25; let baseMana=100+(level-1)*10; maxHp=Math.floor(baseHp*vocs[v].hpMult); maxMana=Math.floor(baseMana*vocs[v].manaMult); hp=maxHp; mana=maxMana; log('🧙 Você agora é '+v+'! Skill: '+vocs[v].skill); update(); }
function changeMap(m){ currentMap=m; document.querySelectorAll('.map').forEach(e=>e.classList.remove('active')); document.getElementById('map-'+m).classList.add('active'); spawnMonster(false); log('🗺️ Foi para '+m); update(); }
function spawnMonster(boss=false){ isBoss=boss; let list=maps[currentMap].list; let m=list[Math.min(Math.floor(level/15),list.length-1)]; if(boss) m={e:'👹',n:'BOSS '+m.n}; mLevel=boss?level+5:level; mMax=boss?300+level*40:40+level*15; mHp=mMax; document.getElementById('monster').innerText=m.e; document.getElementById('monsterName').innerText=m.e+' '+m.n+' - Lvl '+mLevel+' | '+currentMap.toUpperCase()+(boss?' [BOSS 4x]':''); update(); }
function attack(){
 if(hp<=0){hp=maxHp; log('💀 Morreu, HP restaurado'); update(); return;}
 let b=getBoost(); let hit=Math.floor((dmg+Math.random()*dmg)*vocs[voc].dmgMult); if(voc=='Paladin' && Math.random()<0.3){hit*=2; log('🎯 CRÍTICO PALADIN!');} mHp-=hit;
 let mDmg=Math.floor(Math.random()*(4+level))+(isBoss?15:2); hp-=mDmg; if(hp<0) hp=0; if(voc=='Monk'){ let heal=Math.floor(hit*0.2); hp=Math.min(maxHp,hp+heal); }
 if(voc=='Druid'){ hp=Math.min(maxHp,hp+2); mana=Math.min(maxMana,mana+5); }
 mana=Math.min(maxMana,mana+3);
 log(`⚔️ Deu ${hit}. Tomou ${mDmg}.`);
 if(mHp<=0){
  let xpGain=Math.floor((20+mLevel*10)*9.99*maps[currentMap].x*b.xpB);
  let goldGain=Math.floor((10+Math.random()*30)*maps[currentMap].g*(isBoss?4:1)*(voc=='Paladin'?1.3:1));
  xp+=xpGain; gold+=goldGain; log(`🎉 Matou! +${xpGain} XP | +${goldGain} Gold`);
  let dropCount=(isBoss||currentMap=='inferno'?4:2)*b.lootB; let lootDiv=document.getElementById('loot'); lootDiv.innerHTML='';
  for(let i=0;i<dropCount;i++){ let it=loots[Math.floor(Math.random()*loots.length)]; lootDiv.innerHTML+=`<span class="item">${it}</span>`; if(it.includes('Gold')) gold+=5; if(it.includes('Potion')) pot+=1; }
  log(`📦 DROP ${dropCount}x!`);
  while(xp>=xpNeed){xp-=xpNeed; level++; xpNeed=Math.floor(xpNeed*1.25); maxHp+=25; hp=maxHp; dmg+=8; maxMana+=10; log(`🔥 LEVEL UP! Level ${level}!`);}
  spawnMonster(false);
 }
 update();
}
function useSkill(){
 if(skillCd>0){log('⏳ Skill em cooldown '+skillCd+'s'); return;}
 if(mana<30){log('❌ Sem mana!'); return;}
 mana-=30; skillCd=8;
 if(voc=='Knight'){ let d=dmg*2; mHp-=d; log(`⚔️ EXORI! ${d} dano em área!`); }
 if(voc=='Mage'){ let d=dmg*3; mHp-=d; log(`🔥 EXORI FLAM! ${d} dano mágico!`); }
 if(voc=='Druid'){ hp=maxHp; log(`🌿 EXURA VITA! HP full!`); }
 if(voc=='Paladin'){ let d=dmg*2.5; if(Math.random()<0.5){d*=2; log('🎯 CRÍTICO!');} mHp-=d; log(`🏹 EXORI SAN! ${d} dano!`); }
 if(voc=='Monk'){ let total=0; for(let i=0;i<5;i++){ let h=Math.floor(dmg*0.6); total+=h; mHp-=h; } let heal=Math.floor(total*0.4); hp=Math.min(maxHp,hp+heal); log(`🥋 EXORI FIST! 5 hits = ${total} dano + ${heal} HP roubado!`); }
 if(mHp<=0){ attack(); } update();
}
function usePotion(){ if(pot<=0){log('❌ Sem potion');return;} pot--; hp=Math.min(maxHp,hp+50); mana=Math.min(maxMana,mana+30); log('🧪 +50 HP +30 Mana'); update(); }
function spawnBoss(){ spawnMonster(true); log('👹 BOSS! Drop 4x'); }
function buyTC(q){ let cost=q*100; if(q==50) cost=4500; if(gold>=cost){gold-=cost; tc+=q; log(`🪙 Comprou ${q} TC!`);} else log('❌ Gold insuficiente'); update(); }
function buyStore(item){ if(item=='xpboost' && tc>=20){tc-=20; boostXpUntil=Date.now()+5*60000; log('🚀 XP Boost 2x por 5 min!');} else if(item=='lootboost' && tc>=20){tc-=20; boostLootUntil=Date.now()+5*60000; log('📦 Loot Boost 2x por 5 min!');} else if(item=='outfit' && tc>=30){tc-=30; outfit='👑 Premium'; log('👑 Outfit Premium equipado!');} else if(item=='mount' && tc>=30){tc-=30; mount=true; log('🐎 Mount comprado!');} else if(item=='hp' && gold>=150){gold-=150; maxHp+=50; hp=maxHp; log('❤️ +50 HP');} else log('❌ Saldo insuficiente'); update(); }
function updateRank(){ let r=JSON.parse(localStorage.getItem('hunter_rank')||'[]'); let name=document.getElementById('playerName').value||'Você'; r=r.filter(x=>x.name!==name); r.push({name,level,gold}); r.sort((a,b)=>b.level-a.level); r=r.slice(0,5); localStorage.setItem('hunter_rank',JSON.stringify(r)); let h=''; r.forEach((x,i)=>{h+=`<div style="display:flex;justify-content:space-between;padding:8px;background:#2a2a45;border-radius:8px;margin-top:6px"><span>${i+1}º ${x.name}</span><b>Lvl ${x.level}</b></div>`}); document.getElementById('ranking').innerHTML=h; }
setInterval(()=>{ if(skillCd>0) skillCd--; if(hp<maxHp) hp=Math.min(maxHp,hp+1); if(mana<maxMana) mana=Math.min(maxMana,mana+2); update(); },1000);
if(!S.level) log('Bem-vindo! Escolha sua vocação e comece a hunt 999x!');
else log('Bem-vindo de volta! Level '+level+' carregado!');
changeMap(currentMap); updateRank();
</script>
</body>
</html>
