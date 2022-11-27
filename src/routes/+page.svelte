<script>
	import NavBar from '../lib/NavBar.svelte';
	import Footer from '../lib/Footer.svelte';
</script>

<NavBar />

<!-- Hero Image -->
<img src="heroHome.png" alt="" class="w-full" />

<!-- Page Content -->
<div class="text-3xl text-amber-900 flex justify-center mt-12 mb-8">
	<h1>Irmãs de Santa Catarina</h1>
</div>

<!-- Blocks -->
<div class="flex items-center justify-center gap-6 mb-8">
	<img src="block-1.png" alt="" />
	<img src="block-2.png" alt="" />
	<img src="block-3.png" alt="" />
</div>
<div class="px-80 mb-20">
	<p class="text-sm text-amber-900 text-center">
		No ano de 1552, na cidade de Braunsberg - hoje Braniewo, (Polônia), Deus chama à vida Regina
		Protmann, no seio de uma família rica e piedosa, onde recebe boa educação intelectual, moral e
		religiosa. Seu lema de vida, COMO DEUS QUISER, trazia seu jeito de ser com Deus e com os outros.
		Foi no interior do coração generoso desta jovem que nasceu a Congregação das Irmâs de Santa
		Catarina, VM.
	</p>
</div>

<div class="flex w-full justify-center space-x-24">
	<!-- Seção Novidades -->
	<div class="">
		<div class="border-b border-neutral-100 pb-4">
			<h2 class="text-3xl text-amber-900">Novidades</h2>
			<button class="text-xs text-yellow-500 font-bold uppercase pt-2">Ver todas >></button>
		</div>
		<img src="flor.png" alt="" class="mt-6" />
		<div class="flex w-full justify-between pt-4">
			<h3 class="text-xs text-neutral-400 font-semibold uppercase tracking-widest">Meditações</h3>
			<h3 class="text-xs text-neutral-400">14/AGO</h3>
		</div>
		<div class="text-amber-900">
			<h3 class="text-lg font-semibold">Lorem Ipsum Sit Dolor</h3>
			<p class="text-sm max-w-xl">
				Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ad unde at omnis maxime,
				blanditiis consequatur beatae! Molestias sint accusamus magnam
			</p>
		</div>
		<img src="flor2.png" alt="" class="mt-6" />
		<div class="flex w-full justify-between pt-4">
			<h3 class="text-xs text-neutral-400 font-semibold uppercase tracking-widest">Mensagens</h3>
			<h3 class="text-xs text-neutral-400">14/AGO</h3>
		</div>
		<div class="text-amber-900">
			<h3 class="text-lg font-semibold">Lorem Ipsum Sit Dolor</h3>
			<p class="text-sm max-w-xl mb-20">
				Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ad unde at omnis maxime,
				blanditiis consequatur beatae! Molestias sint accusamus magnam
			</p>
		</div>
	</div>

	<!-- Seção Reflexões -->
	<div class="w-64 -translate-x-14">
		<div class=" border-b border-neutral-100 pb-4">
			<h2 class="text-3xl text-amber-900">Reflexões</h2>
			<button class="text-xs text-yellow-500 font-bold uppercase pt-2">Ver todas >></button>
		</div>
		<div class="mb-8">
			<p class="text-xs text-neutral-400 mt-6">14/AGO</p>
			<p class="text-md text-amber-900 font-bold">Meu recado</p>
		</div>
		<div class="mb-8">
			<p class="text-xs text-neutral-400 mt-4">14/AGO</p>
			<p class="text-md text-amber-900 font-bold">
				Regina Protmann - Fundadora da Congregação das Irmãs da Santa Catarina, V.M.
			</p>
		</div>
		<div class="mb-8">
			<p class="text-xs text-neutral-400 mt-4">14/AGO</p>
			<p class="text-md text-amber-900 font-bold">O Doce Jesus</p>
		</div>
		<div class="mb-8">
			<p class="text-xs text-neutral-400 mt-4">14/AGO</p>
			<p class="text-md text-amber-900 font-bold">Cem anos de História</p>
		</div>
	</div>
</div>

<div class="px-80 mb-20">
	<img src="valor.png" alt="" />
</div>

<div class="text-3xl text-amber-900 px-80 mb-6">
	<h1 class="font-semibold">Galeria</h1>
</div>
<div class="flex w-full justify-center space-x-24">
	<!-- Seção Livros -->
	<div class="">
		<div class="border-b border-neutral-100 pb-4">
			<h2 class="text-xl font-bold text-amber-900">Livros</h2>
			<button class="text-xs text-yellow-500 font-bold uppercase pt-2">Ver todas >></button>
		</div>
		<div class="flex justify-center items-center gap-6 mt-6 mb-28">
			<img src="livro1.png" alt="" class="shadow-md" />
			<img src="livro2.png" alt="" class="shadow-md" />
		</div>
	</div>

	<!-- Seção Aúdios -->
	<div class="w-64 -translate-x-14">
		<div class=" border-b border-neutral-100 pb-4">
			<h2 class="text-xl font-bold text-amber-900">Aúdios</h2>
			<button class="text-xs text-yellow-500 font-bold uppercase pt-2">Ver todas >></button>
		</div>
		<div class="mt-7">
			<div class="w-80 h-24 p-4 border border-solid shadow-md rounded-md">
				<h2 class="text-lg font-bold text-amber-900">Nome do áudio 1</h2>
				<img src="play.png" alt="" class="" />
			</div>
		</div>
		<div class="mt-7">
			<div class="w-80 h-24 p-4 border border-solid shadow-md rounded-md">
				<h2 class="text-lg font-bold text-amber-900">Nome do áudio 2</h2>
				<img src="play.png" alt="" class="" />
			</div>
		</div>
		<div class="mt-7">
			<div class="w-80 h-24 p-4 border border-solid shadow-md rounded-md">
				<h2 class="text-lg font-bold text-amber-900">Nome do áudio 3</h2>
				<img src="play.png" alt="" class="" />
			</div>
		</div>
	</div>
</div>

<Footer />
