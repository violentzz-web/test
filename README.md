<div class="heart"></div>
<style>
.heart{
  width:100px;height:90px;position:relative;transform:rotate(-45deg);
  background:red;margin:20px;
}
.heart::before,.heart::after{
  content:"";position:absolute;width:100px;height:100px;background:red;border-radius:50%;
}
.heart::before{top:-50px;left:0}
.heart::after{left:50px;top:0}
</style>