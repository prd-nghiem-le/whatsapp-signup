<script setup>
useHead({
  title: "WhatsApp Signup",
});
</script>

<template>
  <div class="p-[10px] flex justify-center">
    <div class="container border border-1 shadow py-[24px] px-[40px] w-full flex flex-col gap-[16px]">
      <h3 class="">Log in with Facebook</h3>
      <div>
        In order to start communicating with your candidates/employees via
        WhatsApp, please complete the following self-serve WhatsApp onboarding.
      </div>
      <button
        onclick="launchEmbeddedSignup()"
        style="
          background-color: #1877f2;
          border: 0;
          border-radius: 4px;
          color: #fff;
          cursor: pointer;
          font-family: Helvetica, Arial, sans-serif;
          font-size: 16px;
          font-weight: bold;
          height: 40px;
          padding: 0 24px;
        "
      >
        Login with Facebook
      </button>
    </div>
  </div>
</template>
