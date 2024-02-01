<script setup>

</script>

<template>
  <nav class="navbar navbar-expand-lg navbar-dark shadow" style="background: #7f00ff;">
    <div class="container">
      <a class="navbar-brand" href="#">นายมาร์ก</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">หน้าแรก</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">บุคคลากร</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              เกี่ยวกับเรา
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">ประวัติความเป็นมา</a></li>
              <li><a class="dropdown-item" href="#">วิสัยทัศน์</a></li>
              <li><a class="dropdown-item" href="#">บุคลากร</a></li>
              <li><hr class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="#">แผนที่</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" aria-disabled="true" href="#">ติดต่อเรา</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <router-view />
</template>

<style lang="scss" scoped>

</style>