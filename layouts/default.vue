<template>
  <div id="wrapper">
    <!-- Sidebar -->
    <v-sidebar />
    <!-- End of Sidebar -->

    <!-- Content Wrapper -->
    <div id="content-wrapper" class="d-flex flex-column">
      <!-- Main Content -->
      <div id="content">
        <!-- Topbar -->
        <v-topbar />
        <!-- End of Topbar -->

        <!-- Begin Page Content -->
        <Nuxt />
        <!-- /.container-fluid -->
      </div>
      <!-- End of Main Content -->

      <!-- Footer -->
      <v-footer />
      <!-- End of Footer -->
    </div>
    <!-- End of Content Wrapper -->
  </div>
</template>

<script>
export default {}
</script>
