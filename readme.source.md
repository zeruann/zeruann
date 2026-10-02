```aura width=860 height=200
<div style={{
  width: '100%', height: '100%', display: 'flex', alignItems: 'center',
  fontFamily: 'Inter', position: 'relative', overflow: 'hidden', borderRadius: 24,
  backgroundImage: 'linear-gradient(135deg, #FFF3F8 0%, #FBDDEB 55%, #E6DCFA 100%)',
  border: '2px solid #F8C8DC'
}}>

  <div style={{
    position: 'absolute', left: 48, top: 52, width: 96, height: 96,
    borderRadius: 48, backgroundImage: 'linear-gradient(135deg, #FF9FC4, #C9B6F2)',
    display: 'flex', alignItems: 'center', justifyContent: 'center',
  }}>
    <img src={github?.user?.avatarUrl ?? 'https://github.com/zeruann.png'} width={88} height={88} style={{ borderRadius: 44 }} />
  </div>

  <div style={{ display: 'flex', flexDirection: 'column', marginLeft: 168, gap: 8 }}>
    <div style={{ display: 'flex', fontSize: 38, fontWeight: 800, color: '#5A2A3A', letterSpacing: '-1px', lineHeight: 1 }}>
      {github?.user?.name || github?.user?.login || 'zeruann'}
    </div>
    <div style={{ display: 'flex', fontSize: 15, color: '#8A6478' }}>
      A student passionate about building things
    </div>
  </div>
</div>
```

## Tech stack

```aura width=860 height=130
<div style={{ display: 'flex', flexWrap: 'wrap', alignItems: 'center', width: '100%', height: '100%', gap: 10, padding: 8, fontFamily: 'Inter' }}>
  {['React', 'TypeScript', 'JavaScript', 'Node.js', 'MongoDB', 'C#', 'Python', 'Figma', 'HTML', 'CSS'].map(function(t) {
    return (
      <div key={t} style={{ display: 'flex', padding: '10px 20px', borderRadius: 999, backgroundColor: '#FFF3F8', border: '2px solid #F8C8DC', color: '#5A2A3A', fontSize: 18, fontWeight: 600 }}>{t}</div>
    );
  })}
</div>
```

## Projects

```aura width=280 height=150 link="https://github.com/zeruann/hazelportfolio" inline align=center
<div style={{ display: 'flex', width: '100%', height: '100%', padding: '0 8px' }}>
<div style={{ display: 'flex', flexDirection: 'column', justifyContent: 'space-between', width: '100%', height: '100%', padding: 22, borderRadius: 20, backgroundImage: 'linear-gradient(135deg, #FFFFFF 0%, #FDEAF2 100%)', border: '2px solid #F8C8DC', fontFamily: 'Inter' }}>
  <div style={{ display: 'flex', flexDirection: 'column' }}>
    <div style={{ display: 'flex', fontSize: 20, fontWeight: 800, color: '#5A2A3A' }}>hazelportfolio</div>
    <div style={{ display: 'flex', fontSize: 14, color: '#8A6478', marginTop: 8 }}>Portfolio</div>
  </div>
  <div style={{ display: 'flex', fontSize: 14, color: '#C2467D' }}>HTML</div>
</div>
</div>
```
```aura width=280 height=150 link="https://github.com/zeruann/BayanUprisingJuanRevolution_LiwanagStudios" inline align=center
<div style={{ display: 'flex', width: '100%', height: '100%', padding: '0 8px' }}>
<div style={{ display: 'flex', flexDirection: 'column', justifyContent: 'space-between', width: '100%', height: '100%', padding: 22, borderRadius: 20, backgroundImage: 'linear-gradient(135deg, #FFFFFF 0%, #FDEAF2 100%)', border: '2px solid #F8C8DC', fontFamily: 'Inter' }}>
  <div style={{ display: 'flex', flexDirection: 'column' }}>
    <div style={{ display: 'flex', fontSize: 20, fontWeight: 800, color: '#5A2A3A' }}>Bayan Uprising</div>
    <div style={{ display: 'flex', fontSize: 14, color: '#8A6478', marginTop: 8 }}>T140</div>
  </div>
  <div style={{ display: 'flex', fontSize: 14, color: '#C2467D' }}>Java</div>
</div>
</div>
```
```aura width=280 height=150 link="https://github.com/zeruann/MediFind_RocketLabs" inline align=center
<div style={{ display: 'flex', width: '100%', height: '100%', padding: '0 8px' }}>
<div style={{ display: 'flex', flexDirection: 'column', justifyContent: 'space-between', width: '100%', height: '100%', padding: 22, borderRadius: 20, backgroundImage: 'linear-gradient(135deg, #FFFFFF 0%, #FDEAF2 100%)', border: '2px solid #F8C8DC', fontFamily: 'Inter' }}>
  <div style={{ display: 'flex', flexDirection: 'column' }}>
    <div style={{ display: 'flex', fontSize: 20, fontWeight: 800, color: '#5A2A3A' }}>MediFind RocketLabs</div>
    <div style={{ display: 'flex', fontSize: 14, color: '#8A6478', marginTop: 8 }}>Team project (fork)</div>
  </div>
  <div style={{ display: 'flex', fontSize: 14, color: '#C2467D' }}>PHP</div>
</div>
</div>
```