<script>
    export let size = 24;
    export let color = "currentColor";
    export let strokeWidth = 2;
    let className = ''
    export { className as class }
</script>

<svg
    xmlns='http://www.w3.org/2000/svg'
    class='icon icon-tabler icon-tabler-%%ORIGINAL_NAME%% {className}'
    width={size}
    height={size}
    viewBox='0 0 24 24'
    stroke={color}
    stroke-width={strokeWidth}
    fill='none'
    stroke-linecap='round'
    stroke-linejoin='round'
>
      %%SVG_CONTENT%%
</svg>