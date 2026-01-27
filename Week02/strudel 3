samples({
yes: 'https://cdn.freesound.org/previews/151/151332_2688088-lq.mp3',
click: 'https://cdn.freesound.org/previews/644/644693_13590673-lq.mp3',
go: 'https://cdn.freesound.org/previews/625/625810_1540717-lq.mp3',
cat: 'https://cdn.freesound.org/previews/331/331405_3063784-lq.mp3',
  })
setcps (120/80/4)
d1: s("yes:2").euclid(5,8).off(1/4, add(2)).delay(0.2).pan(1).gain(0.4)
$: s("kick:4").euclid(3,5).off(1/4, add(1)).delay(0.1).pan(1).gain(0.2)
$: s("[go:2*16?0.2|cat:2*1]") .delay(0).pan(1).gain(0.4)
