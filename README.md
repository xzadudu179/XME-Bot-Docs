# 开始使用

<script>
    const mainElement = document.querySelector('main');
    const navElement = document.querySelector('nav');

    if (mainElement.classList.contains('hidden')) {
      navElement.style.display = 'none';
    } else {
      navElement.style.display = '';
    }
</script>