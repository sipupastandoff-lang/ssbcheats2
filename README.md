<div class="small">Интуитивный интерфейс и шаблоны для популярных задач.</div>
        </div>
        <div class="feature">
          <h4>Быстрота</h4>
          <div class="small">Применение патчей в несколько кликов, поддержка пакетной обработки.</div>
        </div>
        <div class="feature">
          <h4>Безопасность</h4>
          <div class="small">Авто-резервные копии и режим "dry-run" для проверки без изменений.</div>
        </div>
        <div class="feature">
          <h4>Гибкость</h4>
          <div class="small">Поддержка пользовательских скриптов и форматов патчей.</div>
        </div>
      </div>

    </section>

    <section class="card" style="margin-top:16px">
      <h3 id="download">Скачать & Установить</h3>
      <p class="small">Выберите сборку для вашей ОС. Ссылки ведут на релизы GitHub.</p>
      <div style="display:flex;gap:8px;margin-top:10px;flex-wrap:wrap">
        <a class="btn" href="#">Windows x64 (.exe)</a>
        <a class="btn" href="#">Linux x64 (.AppImage)</a>
        <a class="btn" href="#">macOS (.dmg)</a>
      </div>

      <h4 style="margin-top:14px">Быстрая установка (пример для Linux)</h4>
      <pre><code>sudo chmod +x polar-patcher.AppImage

./polar-patcher.AppImage </code></pre>

<h4 style="margin-top:12px">Пример использования</h4>
      <pre><code># Применить патч

polar-patcher --apply mypatch.json --target path/to/file

Просмотреть изменения (dry-run)

polar-patcher --dry-run --apply mypatch.json --target path/to/file </code></pre> </section>

<section class="card" style="margin-top:16px">
      <h3>FAQ</h3>
      <div class="small">
        <strong>Поддерживает ли Polar Patcher автоматическое откатывание?</strong>
        <p>Да — при каждом применении создаётся резервная копия. Откат можно выполнить через интерфейс или CLI.</p>

        <strong>Какие форматы патчей поддерживаются?</strong>
        <p>JSON-патчи (встроенный формат), бинарные диффы и пользовательские плагины.</p>

        <strong>Можно ли интегрировать в CI/CD?</strong>
        <p>Да — есть консольный интерфейс и exit-коды для автоматизации.</p>
      </div>
    </section>

  </main>

  <aside>
    <div class="card">
      <h3>Ключевые ссылки</h3>
      <ul class="small" style="padding-left:16px;margin-top:8px">
        <li>Репозиторий: <a href="https://github.com/your-repo/polar-patcher" target="_blank">github.com/your-repo/polar-patcher</a></li>
        <li>Релизы: <a href="#">Releases</a></li>
        <li>Документация: <a href="#">Docs</a></li>
      </ul>

      <h3 style="margin-top:12px">Быстрая инструкция</h3>
      <ol class="install-steps small">
        <li>Скачать релиз под ОС.</li>
        <li>Создать резервную копию файлов (если нужно).</li>
        <li>Запустить Polar Patcher и выбрать патч / целевой файл.</li>
        <li>Проверить в режиме dry‑run, затем применить.</li>
      </ol>

      <div style="margin-top:12px;text-align:center">
        <a class="btn primary" href="#">Скачать сейчас</a>
      </div>
    </div>

    <div class="card" style="margin-top:12px">
      <h4>Контакты</h4>
      <div class="small">Email: <a href="mailto:hello@polarpatcher.dev">hello@polarpatcher.dev</a></div>
      <div class="small">Twitter: <a href="#">@polar_patcher</a></div>
      <div class="small" style="margin-top:10px">Лицензия: MIT</div>
    </div>
  </aside>
</div>

<footer>
  <div>© Polar Patcher — Все права защищены. Сделано с ♥</div>
</footer>

  </div>
</body>
</html>
