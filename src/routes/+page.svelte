<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>OMI TOKEN</title>
    <link
      href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css"
      rel="stylesheet"
    />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700&display=swap"
      rel="stylesheet"
    />
  </head>
  <body class="font-Montserrat bg-black">
    <nav
      class="nav-main max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4"
    >
      <a
        href=""
        class="animated flex items-center space-x-3 rtl:space-x-reverse"
      >
        <img
          src="/logo.png"
          class="h-12 rounded-full md:h-20"
          alt="logo"
        />
        <span
          class="md:hidden lg:block text-lg md:text-3xl font-extrabold whitespace-nowrap text-blue-500"
          style="px-4 background-image: linear-gradient(to right, rgb(150, 24, 182), violet); color: transparent; -webkit-background-clip: text; background-clip: text;"
          >OMI TOKEN</span
        >
      </a>
      <button
        data-collapse-toggle="navbar-default"
        type="button"
        class="px-4 inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-white rounded-sm md:hidden hover:bg-cyan-500"
        aria-controls="navbar-default"
        aria-expanded="false"
        onclick="toggleMenu()"
      >
        <span class="sr-only">Open main menu</span>
        <span id="menuIcon" class="menu-icon">
          <svg
            class="w-5 h-5"
            aria-hidden="true"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 17 14"
          >
            <path
              class="px-4 stroke-current stroke-linecap-round stroke-linejoin-round stroke-w-2"
              d="M1 1h15M1 7h15M1 13h15"
            ></path>
          </svg>
        </span>
      </button>
      <div class="px-4 w-full md:block md:w-auto hidden" id="navbar-default">
        <ul
          class="px-4 font-medium flex flex-col p-4 md:p-0 mt-4 border rounded-sm md:flex-row md:space-x-8 rtl:space-x-reverse md:mt-0 md:border-0"
        >
          <li>
            <div class="px-4 bg-blue-500 border rounded p-3">
              <a
                href="#home"
                class="px-4 text-white text-lg lg:text-xl hover:text-pink-500 hover:text-xl md:hover:bg-transparent md:border-0 md:hover:text-pink-500 md:p-0 animated"
              >
                <i class="px-4 bx bx-coin"></i> HOME
              </a>
            </div>
          </li>
          <li>
            <div class="px-4 bg-amber-500 border rounded p-3">
              <a
                href="#about"
                class="px-4 text-white text-lg lg:text-xl hover:text-pink-500 hover:text-xl md:hover:bg-transparent md:border-0 md:hover:text-pink-500 md:p-0 animated"
              >
                <i class="px-4 bx bx-coin"></i> ABOUT
              </a>
            </div>
          </li>
          <li>
            <!-- <div class="px-4 bg-green-500 border rounded p-3">
  <a
    href="#tokenomics"
    class="px-4 text-white text-lg lg:text-xl hover:text-pink-500 hover:text-xl md:hover:bg-transparent md:border-0 md:hover:text-pink-500 md:p-0 animated"
  >
    <i class="px-4 bx bx-coin"></i> TOKENOMICS
  </a>
</div> -->
          </li>
          <li>
            <div class="px-4 bg-red-500 border rounded p-3">
              <a
                href="#roadmap"
                class="text-white text-lg lg:text-xl hover:text-pink-500 hover:text-xl md:hover:bg-transparent md:border-0 md:hover:text-pink-500 md:p-0 animated"
              >
                <i class="bx bx-coin"></i> ROADMAP
              </a>
            </div>
          </li>
          <li>
            <!-- <div class="bg-purple-500 border rounded p-3">
  <a
    href="#partners"
    class="text-white text-lg lg:text-xl hover:text-pink-500 hover:text-xl md:hover:bg-transparent md:border-0 md:hover:text-pink-500 md:p-0 animated"
  >
    <i class="bx bx-coin"></i> PARTNERS
  </a>
</div> -->

            <div class="my-2 md:block md:w-auto hidden" id="navbar-default-btn">
              <a href="#">
                <button
                  type="button"
                  class="bg-green-500 text-white hover:bg-blue-700 hover:text-white py-2 px-4 border border-blue-500 rounded-full"
                  >Buy Now</button
                >
              </a>
            </div>
          </li>
        </ul>
      </div>
    </nav>

    <section
      id="home"
      class="text-white flex flex-col md:flex-row-reverse items-center justify-center h-screen mb-12"
    >
      <div class="animated flex flex-col items-center text-center">
        <p class="font-serif text-3xl md:text-4xl mt-8">Welcome to OMI TOKEN</p>
        <b>Omchain network's first meme token</b>
        <div class="flex mt-4 space-x-4">
          <a
            href="#"
            target="_blank"
            class="text-white hover:text-gray-300 transition-all duration-300"
          >
            <i class="fab fa-etherscan"></i>
          </a>
          <a
            href="https://x.com/Omimemetoken?t=O-8iv1Qt8Hej0etAuz5l5g&s=09"
            target="_blank"
            class="text-white hover:text-gray-300 transition-all duration-300"
          >
            <i class="fab fa-twitter"></i>
          </a>
          <a
            href="#"
            target="_blank"
            class="text-white hover:text-gray-300 transition-all duration-300"
          >
            <i class="fab fa-telegram"></i>
          </a>
          <button
            class="text-white hover:text-gray-300 transition-all duration-300 focus:outline-none"
          >
            Buy
          </button>
        </div>
      </div>
      <img
        src="/logo.png"
        class="w-48 h-48 md:w-64 md:h-64 mx-auto md:mr-auto"
        alt="Home Image"
      />
    </section>

    <section id="about">
      <div class="px-4 mb-20 container mx-auto">
        <div class="px-4 max-w-4xl mx-auto text-center">
          <h2 class="px-4 text-3xl md:text-4xl font-bold mb-6">
            About OMI Token
          </h2>
          <p class="px-4 text-lg md:text-xl leading-relaxed mb-12">
            OMI MEME is a polar movement dedicated to Crypto lovers. Its sole
            purpose is to earn your friendship, as well as to be a redeemable
            token for new games in the WEB2/WEB3 space.
          </p>
          <p class="px-4 text-lg md:text-xl leading-relaxed mb-12">
            OMI is Charitable
          </p>
          <p class="px-4 text-lg md:text-xl leading-relaxed mb-12">
            OMI has a fluffy heart OMI Doesn't Like Fraud
          </p>
          <p class="px-4 text-lg md:text-xl leading-relaxed mb-12">
            OMI doesn't lie, OMI Loves You
          </p>
        </div>
      </div>
    </section>

    <!-- <section id="tokenomics">
  <div class="px-4 mb-20 container mx-auto">
    <div class="px-4 max-w-4xl mx-auto text-center">
      <h2 class="px-4 text-3xl md:text-4xl font-bold mb-8">Tokenomics</h2>
      <div class="grid px-4  grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="bg-gray-900 px-4 rounded-lg p-6">
          <h3 class="text-xl font-semibold px-4  mb-4">Total Supply</h3>
          <p class="px-4 text-lg">1,000,000,000,000</p>
        </div>
        <div class="px-4 bg-gray-900 rounded-lg p-6">
          <h3 class="px-4 text-xl font-semibold mb-4">Token Name</h3>
          <p class="text-lg px-4 ">Penguin Token</p>
        </div>
        <div class="bg-gray-900 px-4 rounded-lg p-6">
          <h3 class="text-xl px-4  font-semibold mb-4">Symbol</h3>
          <p class="text-lg px-4 ">PGN</p>
        </div>
        <div class="bg-gray-900 px-4 rounded-lg p-6">
          <h3 class="text-xl px-4 font-semibold mb-4">Initial Liquidity</h3>
          <p class="text-lg px-4 ">$500,000</p>
        </div>
        <div class="bg-gray-900 px-4 rounded-lg p-6">
          <h3 class="text-xl px-4 font-semibold mb-4">Distribution</h3>
          <p class="text-lg px-4 ">50% Burned, 40% Liquidity, 10% Dev Fund</p>
        </div>
        <div class="bg-gray-900 px-4 rounded-lg p-6">
          <h3 class="text-xl px-4 font-semibold mb-4">Token Type</h3>
          <p class="text-lg px-4 ">ERC-20</p>
        </div>
      </div>
    </div>
  </div>
</section> -->

    <section id="roadmap">
      <div class="mb-20 px-4 container mx-auto">
        <div class="max-w-4xl px-4 mx-auto text-center">
          <h2 class="text-3xl px-4 md:text-4xl font-bold mb-8">Roadmap</h2>
          <div class="grid grid-cols-1 px-4 md:grid-cols-3 gap-8">
            <div class="roadmap-milestone px-4 bg-blue-500">
              <h3 class="text-xl font-semibold px-4 mb-2">Pre-sale</h3>
              <p class="text-gray-100 px-4">
                This typically refers to a phase before the official launch of a
                project where a limited number of tokens are offered for sale to
                early investors or supporters. Pre-sale participants often get
                tokens at a discounted price compared to the public sale.
              </p>
            </div>
            <div class="roadmap-milestone px-4 bg-green-500">
              <h3 class="text-xl font-semibold px-4 mb-2">Launch</h3>
              <p class="text-gray-100 px-4">
                This marks the official start of the project. It could involve
                the release of a product, platform, or service to the public, or
                the initiation of operations in the case of a business.
              </p>
            </div>
            <div class="roadmap-milestone px-4 bg-yellow-500">
              <h3 class="text-xl font-semibold px-4 mb-2">Listing</h3>
              <p class="text-gray-100 px-4">
                Listing refers to the process of getting a project's token
                listed on cryptocurrency exchanges. Being listed on exchanges
                increases the token's liquidity and accessibility, allowing more
                people to trade it.
              </p>
            </div>
            <div class="roadmap-milestone px-4 bg-red-500">
              <h3 class="text-xl font-semibold px-4 mb-2">Partnership</h3>
              <p class="text-gray-100 px-4">
                Partnership involves forming alliances or collaborations with
                other projects, companies, or organizations. Partnerships can
                help in various ways such as expanding reach, accessing
                resources, or enhancing credibility.
              </p>
            </div>
            <div class="roadmap-milestone px-4 bg-purple-500">
              <h3 class="text-xl font-semibold px-4 mb-2">Nft collection</h3>
              <p class="text-gray-100 px-4">
                NFT (Non-Fungible Token) collection refers to the creation and
                release of unique digital assets on a blockchain. These assets,
                often in the form of digital art, collectibles, or virtual real
                estate, are tokenized and can be bought, sold, or traded.
              </p>
            </div>
            <div class="roadmap-milestone px-4 bg-indigo-500">
              <h3 class="text-xl font-semibold px-4 mb-2">Game</h3>
              <p class="text-gray-100">
                This could refer to the development and launch of a
                blockchain-based game or gaming platform. Blockchain technology
                offers unique features such as asset ownership, digital
                scarcity, and decentralized economies, which can enhance gaming
                experiences and enable new gameplay mechanics.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- <section id="partners">
  <div class="mb-20 container mx-auto">
    <div class="max-w-4xl mx-auto text-center">
      <h2 class="text-3xl md:text-4xl font-bold mb-8">Partners</h2>
      <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
        <div class="partner-logo">
          <img src="partner1.png" alt="Partner 1" />
        </div>
        <div class="partner-logo">
          <img src="partner2.png" alt="Partner 2" />
        </div>
        <div class="partner-logo">
          <img src="partner3.png" alt="Partner 3" />
        </div>
        <div class="partner-logo">
          <img src="partner4.png" alt="Partner 4" />
        </div>
      </div>
    </div>
  </div>
</section> -->

    <footer class="bg-gray-800 text-white py-8">
      <div class="container mx-auto">
        <div class="flex flex-col md:flex-row items-center justify-between">
          <div class="text-center md:text-left">
            <p class="text-lg font-semibold">OMI TOKEN</p>
            <p class="text-sm">© 2024 All rights reserved</p>
          </div>
          <div class="mt-4 md:mt-0">
            <ul
              class="flex items-center justify-center md:justify-end space-x-4"
            >
              <li>
                <a href="#" class="text-gray-400 hover:text-white"
                  ><i class="fab fa-twitter"></i></a
                >
              </li>
              <li>
                <a href="#" class="text-gray-400 hover:text-white"
                  ><i class="fab fa-telegram"></i></a
                >
              </li>
              <li>
                <a href="#" class="text-gray-400 hover:text-white"
                  ><i class="fab fa-discord"></i></a
                >
              </li>
            </ul>
          </div>
        </div>
      </div>
    </footer>

    <script>
      function toggleMenu() {
        var menuIcon = document.getElementById("menuIcon");
        menuIcon.classList.toggle("open");
        var navbar = document.getElementById("navbar-default");
        navbar.classList.toggle("hidden");
      }
    </script>
  </body>
</html>