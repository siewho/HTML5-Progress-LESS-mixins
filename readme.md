HTML5 <Progress> LESS mixins 0.1
===========  




Sample.less
-------------------------

@import "progress.less";

progress {
  .progress();
  margin:10px 0 0;
}
progress.example2 {
  .progress(#cdcdcd,green,2px, 220px, 12px);
  margin:10px 0 0;
}
progress.example3 {
  .progress(#cdcdcd,blue,10px, 180px, 20px);
  margin:10px 0 0;
}

