<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>English A2+ | Present Simple vs Continuous | Полный урок 15 заданий (по 5 пунктов)</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html2pdf.js/0.10.1/html2pdf.bundle.min.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,300;400;500;600;700&family=Quicksand:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
            font-family: 'Inter', sans-serif;
            padding: 30px 20px;
            min-height: 100vh;
        }
        .lesson-wrapper { max-width: 1400px; width: 100%; margin: 0 auto; }
        .lesson-container { background: #ffffff; border-radius: 48px; box-shadow: 0 30px 60px rgba(0,0,0,0.4); overflow: hidden; }
        
        @media print {
            body { background: white; padding: 0; margin: 0; }
            .no-print { display: none !important; }
            .lesson-container { box-shadow: none; border-radius: 0; }
            .task-card, .story-card { break-inside: avoid; page-break-inside: avoid; }
        }
        
        .lesson-header {
            background: linear-gradient(120deg, #0f2b3d, #1b4d6e);
            padding: 2rem 2rem;
            color: white;
        }
        .lesson-header h1 { font-family: 'Quicksand', sans-serif; font-size: 2.3rem; display: flex; align-items: center; gap: 15px; }
        .badge-container { display: flex; flex-wrap: wrap; gap: 12px; margin-top: 15px; }
        .level-badge { background: rgba(255,215,0,0.3); border-radius: 60px; padding: 6px 18px; font-weight: 600; }
        .grammar-badge { background: #2dd4bf; color: #0f172a; border-radius: 60px; padding: 6px 18px; font-weight: 700; }
        .task-count-badge { background: #f59e0b; color: #0f172a; border-radius: 60px; padding: 6px 18px; font-weight: 700; }
        
        .toolbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 2rem;
            background: #f8fafc;
            border-bottom: 2px solid #e2e8f0;
            flex-wrap: wrap;
            gap: 12px;
        }
        .btn {
            border: none;
            font-weight: 600;
            padding: 10px 24px;
            border-radius: 40px;
            cursor: pointer;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            transition: 0.2s;
        }
        .btn-pdf { background: #dc2626; color: white; }
        .btn-html { background: #10b981; color: white; }
        .btn-save { background: #3b82f6; color: white; }
        .btn-load { background: #8b5cf6; color: white; }
        
        .lesson-content { padding: 2rem; }
        .section-title {
            font-size: 1.8rem;
            font-weight: 700;
            color: #0f172a;
            margin: 2rem 0 1.2rem 0;
            border-left: 8px solid #f59e0b;
            padding-left: 20px;
        }
        
        .vocab-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(160px, 1fr)); gap: 20px; margin: 25px 0; }
        .vocab-card {
            background: linear-gradient(135deg, #fff5eb, #ffe8d9);
            border-radius: 28px;
            padding: 1rem;
            text-align: center;
            cursor: pointer;
            transition: 0.2s;
            border: 1px solid #ffd9b5;
        }
        .vocab-card:hover { transform: translateY(-4px); box-shadow: 0 12px 24px rgba(0,0,0,0.1); }
        .vocab-icon { font-size: 2.5rem; }
        .vocab-word { font-size: 1.3rem; font-weight: 700; color: #c2410c; }
        .vocab-meaning { background: white; display: inline-block; padding: 4px 12px; border-radius: 30px; font-size: 0.
75rem; margin-top: 8px; }
        
        .story-card {
            background: linear-gradient(115deg, #fef9e6, #fff4e0);
            border-radius: 40px;
            padding: 2rem;
            margin: 1rem 0;
            border: 2px solid #ffde9c;
        }
        .story-text { font-size: 1.05rem; line-height: 1.7; color: #2d2a1e; }
        .story-text p { margin-bottom: 1rem; }
        .ps-highlight { background: #bbf7d0; padding: 2px 8px; border-radius: 20px; font-weight: 700; cursor: pointer; }
        .pc-highlight { background: #fed7aa; padding: 2px 8px; border-radius: 20px; font-weight: 700; cursor: pointer; }
        
        .task-card {
            background: #f8fafc;
            border-radius: 28px;
            padding: 1.5rem;
            margin: 1.5rem 0;
            border-left: 6px solid #3b82f6;
            box-shadow: 0 2px 8px rgba(0,0,0,0.05);
        }
        .task-title { font-weight: 700; font-size: 1.3rem; margin-bottom: 1.2rem; color: #1e40af; display: flex; align-items: center; gap: 12px; }
        .task-number { background: #3b82f6; color: white; border-radius: 40px; width: 36px; height: 36px; display: inline-flex; align-items: center; justify-content: center; font-size: 1rem; font-weight: bold; }
        .subtask { margin: 15px 0; padding-left: 20px; border-left: 3px solid #cbd5e1; }
        .subtask-title { font-weight: 600; margin-bottom: 8px; color: #334155; }
        .quiz-option {
            background: white;
            border: 2px solid #cbd5e1;
            border-radius: 40px;
            padding: 6px 18px;
            display: inline-block;
            margin: 5px 8px 5px 0;
            cursor: pointer;
            transition: 0.2s;
        }
        .quiz-option:hover { background: #eef2ff; border-color: #3b82f6; }
        .feedback { margin-top: 12px; padding: 10px 16px; border-radius: 28px; font-weight: 500; }
        .correct { background: #d1fae5; color: #065f46; border-left: 4px solid #10b981; }
        .wrong { background: #fee2e2; color: #991b1b; border-left: 4px solid #ef4444; }
        input, textarea, select {
            border: 2px solid #e2e8f0;
            border-radius: 20px;
            padding: 10px 16px;
            width: 100%;
            max-width: 400px;
            margin: 5px 0;
        }
        .btn-small { background: #10b981; color: white; border: none; padding: 8px 24px; border-radius: 40px; cursor: pointer; font-weight: 600; margin-top: 8px; }
        .saved-panel { background: #fef3c7; border-radius: 24px; padding: 1rem; margin-top: 2rem; border-left: 5px solid #f59e0b; }
        .footer { background: #0f172a; color: #94a3b8; padding: 1.5rem; text-align: center; }
        @media (max-width: 768px) { .lesson-content { padding: 1rem; } }
    </style>
</head>
<body>
<div class="lesson-wrapper">
    <div class="lesson-container" id="lessonToExport">
        <div class="lesson-header">
            <h1><i class="fas fa-compass"></i> Mystery in the Jungle</h1>
            <div class="badge-container">
                <span class="level-badge"><i class="fas fa-star"></i> A2+ | Pre-Intermediate</span>
                <span class="grammar-badge"><i class="fas fa-clock"></i> Present Simple vs Present Continuous</span>
                <span class="task-count-badge"><i class="fas fa-tasks"></i> 15 заданий (по 4-5 пунктов каждое)</span>
            </div>
            <p style="margin-top: 12px;"><i class="fas fa-headphones"></i> Нажимайте на выделенные слова — услышите произношение</p>
        </div>
        
        <div class="toolbar no-print">
            <div><span style="background:#e2e8f0; padding:6px 14px; border-radius:40px;"><i class="fas fa-database"></i> Все ответы сохраняются в браузере</span></div>
            <div>
                <button class="btn btn-html" id="saveHtmlBtn"><i class="fas fa-code"></i> HTML</button>
                <button class="btn btn-pdf" id="downloadPdfBtn"><i class="fas fa-file-pdf"></i> PDF</button>
                <button class="btn btn-save" id="saveAllBtn"><i class="fas fa-save"></i> Сохранить</button>
<button class="btn btn-load" id="loadAllBtn"><i class="fas fa-upload"></i> Загрузить</button>
            </div>
        </div>
        
        <div class="lesson-content">
            <!-- VOCABULARY -->
            <div class="section-title"><i class="fas fa-book"></i> 1. Key Vocabulary</div>
            <div class="vocab-grid" id="vocabGrid"></div>
            
            <!-- PRE-READING: ЗАДАНИЯ 1-4 -->
            <div class="section-title"><i class="fas fa-brain"></i> 2. Before Reading</div>
            
            <!-- ЗАДАНИЕ 1: Vocabulary in Context (5 пунктов) -->
            <div class="task-card" id="task1">
                <div class="task-title"><span class="task-number">1</span> Vocabulary in Context</div>
                <div class="subtask">
                    <div class="subtask-title">1.1 Choose the correct meaning of "explorer":</div>
                    <select id="q1_1"><option value="">--</option><option value="correct">A person who travels to discover new places</option><option value="wrong">A person who sleeps a lot</option><option value="wrong">A type of animal</option></select>
                </div>
                <div class="subtask">
                    <div class="subtask-title">1.2 What is a "temple"?</div>
                    <select id="q1_2"><option value="">--</option><option value="correct">An old religious building</option><option value="wrong">A modern school</option><option value="wrong">A jungle tree</option></select>
                </div>
                <div class="subtask">
                    <div class="subtask-title">1.3 "Crystal" means:</div>
                    <select id="q1_3"><option value="">--</option><option value="correct">A shiny precious stone</option><option value="wrong">A piece of wood</option><option value="wrong">A metal tool</option></select>
                </div>
                <div class="subtask">
                    <div class="subtask-title">1.4 "Jungle" is:</div>
                    <select id="q1_4"><option value="">--</option><option value="correct">A thick forest in a tropical area</option><option value="wrong">A desert</option><option value="wrong">A mountain</option></select>
                </div>
                <div class="subtask">
                    <div class="subtask-title">1.5 "Treasure" means:</div>
                    <select id="q1_5"><option value="">--</option><option value="correct">Valuable items like gold and jewels</option><option value="wrong">Ordinary rocks</option><option value="wrong">Old books</option></select>
                </div>
                <button class="btn-small" id="checkTask1">Проверить (1-5)</button>
                <div id="task1Feedback" class="feedback"></div>
            </div>
            
            <!-- ЗАДАНИЕ 2: Predict the Story (5 пунктов) -->
            <div class="task-card">
                <div class="task-title"><span class="task-number">2</span> Prediction</div>
                <div class="subtask"><div class="subtask-title">2.1 Who is the main character?</div><input id="q2_1" placeholder="Your answer..."></div>
                <div class="subtask"><div class="subtask-title">2.2 Where does the story take place?</div><input id="q2_2" placeholder="Your answer..."></div>
                <div class="subtask"><div class="subtask-title">2.3 What do you think they find?</div><input id="q2_3" placeholder="Your answer..."></div>
                <div class="subtask"><div class="subtask-title">2.4 Is there an animal in the story?</div><input id="q2_4" placeholder="Yes/No and what kind?"></div>
                <div class="subtask"><div class="subtask-title">2.5 How does the story end?</div><input id="q2_5" placeholder="Your prediction..."></div>
                <div id="task2Feedback" class="feedback"></div>
            </div>
            
            <!-- ЗАДАНИЕ 3: Grammar Theory (5 пунктов) -->
            <div class="task-card">
                <div class="task-title"><span class="task-number">3</span> Grammar Theory</div>
<div class="subtask"><div class="subtask-title">3.1 Present Simple is used for:</div><select id="q3_1"><option>--</option><option value="correct">Habits, routines, general facts</option><option value="wrong">Actions happening now</option></select></div>
                <div class="subtask"><div class="subtask-title">3.2 Present Continuous is used for:</div><select id="q3_2"><option>--</option><option value="correct">Actions happening right now or around now</option><option value="wrong">Permanent situations</option></select></div>
                <div class="subtask"><div class="subtask-title">3.3 Which sentence is Present Simple?</div><select id="q3_3"><option>--</option><option value="correct">She works every day</option><option value="wrong">She is working now</option></select></div>
                <div class="subtask"><div class="subtask-title">3.4 Which sentence is Present Continuous?</div><select id="q3_4"><option>--</option><option value="correct">He is reading a book</option><option value="wrong">He reads books</option></select></div>
                <div class="subtask"><div class="subtask-title">3.5 Choose the correct form: "The sun ___ in the east."</div><select id="q3_5"><option>--</option><option value="correct">rises</option><option value="wrong">is rising</option></select></div>
                <button class="btn-small" id="checkTask3">Проверить</button>
                <div id="task3Feedback" class="feedback"></div>
            </div>
            
            <!-- ЗАДАНИЕ 4: Signal Words (5 пунктов) -->
            <div class="task-card">
                <div class="task-title"><span class="task-number">4</span> Signal Words</div>
                <div class="subtask"><div class="subtask-title">4.1 "Always" signals:</div><select id="q4_1"><option>--</option><option value="correct">Present Simple</option><option value="wrong">Present Continuous</option></select></div>
                <div class="subtask"><div class="subtask-title">4.2 "Right now" signals:</div><select id="q4_2"><option>--</option><option value="correct">Present Continuous</option><option value="wrong">Present Simple</option></select></div>
                <div class="subtask"><div class="subtask-title">4.3 "Every day" signals:</div><select id="q4_3"><option>--</option><option value="correct">Present Simple</option><option value="wrong">Present Continuous</option></select></div>
                <div class="subtask"><div class="subtask-title">4.4 "At the moment" signals:</div><select id="q4_4"><option>--</option><option value="correct">Present Continuous</option><option value="wrong">Present Simple</option></select></div>
                <div class="subtask"><div class="subtask-title">4.5 "Usually" signals:</div><select id="q4_5"><option>--</option><option value="correct">Present Simple</option><option value="wrong">Present Continuous</option></select></div>
                <button class="btn-small" id="checkTask4">Проверить</button>
                <div id="task4Feedback" class="feedback"></div>
            </div>
            
            <!-- MAIN STORY -->
            <div class="section-title"><i class="fas fa-book-open"></i> 3. The Story</div>
            <div class="story-card">
                <div class="story-text">
                    <p>🌴 <span class="ps-highlight">Leo is</span> a young archaeologist. He <span class="ps-highlight">works</span> at a university, but now he <span class="pc-highlight">is exploring</span> the Amazon jungle. Every morning, he <span class="ps-highlight">wakes up</span> early and <span class="ps-highlight">checks</span> his equipment. Right now, he <span class="pc-highlight">is following</span> a mysterious sound. "What <span class="pc-highlight">is making</span> that noise?" he <span class="ps-highlight">thinks</span>.</p>
                    <p>🗿 Leo's team <span class="ps-highlight">usually stays</span> at the camp, but today they <span class="pc-highlight">are searching</span> for an ancient temple. Suddenly, Leo <span class="ps-highlight">sees</span> something incredible.
"Look! I <span class="pc-highlight">am looking</span> at a stone door!" he <span class="ps-highlight">shouts</span>. A friendly monkey <span class="ps-highlight">appears</span> from the trees. The monkey <span class="ps-highlight">watches</span> Leo carefully. At this moment, the monkey <span class="pc-highlight">is pointing</span> at a symbol on the door.</p>
                    <p>✨ "The monkey <span class="ps-highlight">knows</span> something," Leo <span class="ps-highlight">whispers</span>. He <span class="ps-highlight">touches</span> the symbol, and the door <span class="ps-highlight">opens</span> slowly. Inside, a golden light <span class="ps-highlight">shines</span>. Leo <span class="ps-highlight">sees</span> a crystal that <span class="ps-highlight">glows</span> like the sun. "I <span class="pc-highlight">am not dreaming</span>," he says. While he <span class="pc-highlight">is taking</span> photos, the monkey <span class="ps-highlight">sits</span> beside him. Leo <span class="ps-highlight">understands</span> that true treasure <span class="ps-highlight">is</span> the adventure and friendship. Now he <span class="pc-highlight">is planning</span> to protect this place forever.</p>
                </div>
            </div>
            
            <!-- POST-READING: ЗАДАНИЯ 5-15 (каждое по 5 пунктов) -->
            <div class="section-title"><i class="fas fa-tasks"></i> 4. Comprehension & Grammar (5-15)</div>
            
            <!-- ЗАДАНИЕ 5: True/False (5 пунктов) -->
            <div class="task-card"><div class="task-title"><span class="task-number">5</span> True or False</div>
                <div class="subtask">5.1 Leo is working at the university right now. <select id="tf1"><option>--</option><option value="false">True</option><option value="true">False</option></select> <span id="tf1fb"></span></div>
                <div class="subtask">5.2 The monkey is pointing at a symbol. <select id="tf2"><option>--</option><option value="true">True</option><option value="false">False</option></select> <span id="tf2fb"></span></div>
                <div class="subtask">5.3 Leo takes all the treasure. <select id="tf3"><option>--</option><option value="false">True</option><option value="true">False</option></select> <span id="tf3fb"></span></div>
                <div class="subtask">5.4 The monkey helps Leo open the door. <select id="tf4"><option>--</option><option value="true">True</option><option value="false">False</option></select> <span id="tf4fb"></span></div>
                <div class="subtask">5.5 Leo plans to protect the temple. <select id="tf5"><option>--</option><option value="true">True</option><option value="false">False</option></select> <span id="tf5fb"></span></div>
                <div id="task5Feedback" class="feedback"></div>
            </div>
            
            <!-- ЗАДАНИЕ 6: Multiple Choice (5 пунктов) -->
            <div class="task-card"><div class="task-title"><span class="task-number">6</span> Multiple Choice</div>
                <div class="subtask">6.1 What is Leo doing right now? <select id="mc1"><option>--</option><option value="wrong">Sleeping</option><option value="correct">Exploring the jungle</option><option value="wrong">Teaching</option></select></div>
                <div class="subtask">6.2 Who helps Leo? <select id="mc2"><option>--</option><option value="wrong">A jaguar</option><option value="correct">A monkey</option><option value="wrong">His friend</option></select></div>
                <div class="subtask">6.3 What does Leo find? <select id="mc3"><option>--</option><option value="wrong">Gold coins</option><option value="correct">A crystal</option><option value="wrong">Old books</option></select></div>
                <div class="subtask">6.4 Where is the temple? <select id="mc4"><option>--</option><option value="correct">In the jungle</option><option value="wrong">In the city</option><option value="wrong">On the mountain</option></select></div>
                <div class="subtask">6.
5 What does Leo take? <select id="mc5"><option>--</option><option value="wrong">The crystal</option><option value="correct">A small coin</option><option value="wrong">Nothing</option></select></div>
                <div id="task6Feedback" class="feedback"></div>
            </div>
            
            <!-- ЗАДАНИЕ 7: Find Present Continuous (5 примеров) -->
            <div class="task-card"><div class="task-title"><span class="task-number">7</span> Find 5 Present Continuous examples</div>
                <div class="subtask">7.1 <input id="pc1" placeholder="Example from story..."></div>
                <div class="subtask">7.2 <input id="pc2" placeholder="Example..."></div>
                <div class="subtask">7.3 <input id="pc3" placeholder="Example..."></div>
                <div class="subtask">7.4 <input id="pc4" placeholder="Example..."></div>
                <div class="subtask">7.5 <input id="pc5" placeholder="Example..."></div>
                <button class="btn-small" id="checkTask7">Check</button>
                <div id="task7Feedback" class="feedback"></div>
            </div>
            
            <!-- ЗАДАНИЕ 8: Find Present Simple (5 примеров) -->
            <div class="task-card"><div class="task-title"><span class="task-number">8</span> Find 5 Present Simple examples</div>
                <div class="subtask">8.1 <input id="ps1" placeholder="Example..."></div>
                <div class="subtask">8.2 <input id="ps2" placeholder="Example..."></div>
                <div class="subtask">8.3 <input id="ps3" placeholder="Example..."></div>
                <div class="subtask">8.4 <input id="ps4" placeholder="Example..."></div>
                <div class="subtask">8.5 <input id="ps5" placeholder="Example..."></div>
                <button class="btn-small" id="checkTask8">Check</button>
                <div id="task8Feedback" class="feedback"></div>
            </div>
            
            <!-- ЗАДАНИЕ 9: Complete sentences (5 пунктов) -->
            <div class="task-card"><div class="task-title"><span class="task-number">9</span> Complete with correct form</div>
                <div class="subtask">9.1 Leo usually _ (work) at university. <input id="gap1" placeholder="..."></div>
                <div class="subtask">9.2 Today he _ (explore) the jungle. <input id="gap2" placeholder="..."></div>
                <div class="subtask">9.3 The monkey _ (point) at the door right now. <input id="gap3" placeholder="..."></div>
                <div class="subtask">9.4 The crystal _ (glow) in the temple. <input id="gap4" placeholder="..."></div>
                <div class="subtask">9.5 They _ (take) photos at the moment. <input id="gap5" placeholder="..."></div>
                <button class="btn-small" id="checkTask9">Check</button>
                <div id="task9Feedback" class="feedback"></div>
            </div>
            
            <!-- ЗАДАНИЕ 10: Error correction (5 пунктов) -->
            <div class="task-card"><div class="task-title"><span class="task-number">10</span> Correct the mistakes</div>
                <div class="subtask">10.1 "He are taking photos." → <input id="err1" placeholder="Correct..."></div>
                <div class="subtask">10.2 "She go to school every day." → <input id="err2" placeholder="Correct..."></div>
                <div class="subtask">10.3 "They is playing now." → <input id="err3" placeholder="Correct..."></div>
                <div class="subtask">10.4 "The sun is rising in the east." → <input id="err4" placeholder="Correct..."></div>
                <div class="subtask">10.5 "I am work right now." → <input id="err5" placeholder="Correct..."></div>
                <button class="btn-small" id="checkTask10">Check</button>
                <div id="task10Feedback" class="feedback"></div>
            </div>
            
            <!-- ЗАДАНИЕ 11: Character matching (5 пунктов) -->
            <div class="task-card"><div class="task-title"><span class="task-number">11</span> Who does what? Match</div>
                <div class="subtask">11.
1 Leo (usually) → <select id="char1"><option>--</option><option value="correct">works at university</option><option value="wrong">sleeps</option></select></div>
                <div class="subtask">11.2 Leo (now) → <select id="char2"><option>--</option><option value="correct">is exploring jungle</option><option value="wrong">is sleeping</option></select></div>
                <div class="subtask">11.3 Monkey (now) → <select id="char3"><option>--</option><option value="correct">is pointing at symbol</option><option value="wrong">is running away</option></select></div>
                <div class="subtask">11.4 The team (usually) → <select id="char4"><option>--</option><option value="correct">stays at camp</option><option value="wrong">explores</option></select></div>
                <div class="subtask">11.5 The team (today) → <select id="char5"><option>--</option><option value="correct">is searching for temple</option><option value="wrong">is sleeping</option></select></div>
                <div id="task11Feedback" class="feedback"></div>
            </div>
            
            <!-- ЗАДАНИЕ 12: Time expressions (5 пунктов) -->
            <div class="task-card"><div class="task-title"><span class="task-number">12</span> Choose the correct tense</div>
                <div class="subtask">12.1 "Now" → <select id="time1"><option>--</option><option value="correct">Present Continuous</option><option value="wrong">Present Simple</option></select></div>
                <div class="subtask">12.2 "Every Monday" → <select id="time2"><option>--</option><option value="correct">Present Simple</option><option value="wrong">Present Continuous</option></select></div>
                <div class="subtask">12.3 "At the moment" → <select id="time3"><option>--</option><option value="correct">Present Continuous</option><option value="wrong">Present Simple</option></select></div>
                <div class="subtask">12.4 "Often" → <select id="time4"><option>--</option><option value="correct">Present Simple</option><option value="wrong">Present Continuous</option></select></div>
                <div class="subtask">12.5 "Look!" → <select id="time5"><option>--</option><option value="correct">Present Continuous</option><option value="wrong">Present Simple</option></select></div>
                <div id="task12Feedback" class="feedback"></div>
            </div>
            
            <!-- ЗАДАНИЕ 13: Make sentences (5 пунктов) -->
            <div class="task-card"><div class="task-title"><span class="task-number">13</span> Create your own sentences</div>
                <div class="subtask">13.1 Present Simple about Leo: <input id="create1" placeholder="..."></div>
                <div class="subtask">13.2 Present Continuous about the monkey: <input id="create2" placeholder="..."></div>
                <div class="subtask">13.3 Present Simple about the temple: <input id="create3" placeholder="..."></div>
                <div class="subtask">13.4 Present Continuous about the crystal: <input id="create4" placeholder="..."></div>
                <div class="subtask">13.5 Your own sentence about the story: <input id="create5" placeholder="..."></div>
                <div id="task13Feedback" class="feedback"></div>
            </div>
            
            <!-- ЗАДАНИЕ 14: Choose correct verb (5 пунктов) -->
            <div class="task-card"><div class="task-title"><span class="task-number">14</span> Choose the correct form</div>
                <div class="subtask">14.1 The crystal _ in the temple. <select id="verb1"><option>--</option><option value="glows">glows</option><option value="is glowing">is glowing</option></select></div>
                <div class="subtask">14.2 Look! The monkey _ at us. <select id="verb2"><option>--</option><option value="looks">looks</option><option value="is looking">is looking</option></select></div>
                <div class="subtask">14.3 Leo _ coffee every morning. <select id="verb3"><option>--</option><option value="drinks">drinks</option><option value="is drinking">is drinking</option></select></div>
<div class="subtask">14.4 They _ photos right now. <select id="verb4"><option>--</option><option value="take">take</option><option value="are taking">are taking</option></select></div>
                <div class="subtask">14.5 The sun _ in the east. <select id="verb5"><option>--</option><option value="rises">rises</option><option value="is rising">is rising</option></select></div>
                <div id="task14Feedback" class="feedback"></div>
            </div>
            
            <!-- ЗАДАНИЕ 15: Writing (5 пунктов) -->
            <div class="task-card"><div class="task-title"><span class="task-number">15</span> Creative Writing</div>
                <div class="subtask">15.1 Describe what Leo is doing now (Present Continuous): <textarea id="write1" rows="2" style="width:100%"></textarea></div>
                <div class="subtask">15.2 Describe Leo's daily routine (Present Simple): <textarea id="write2" rows="2" style="width:100%"></textarea></div>
                <div class="subtask">15.3 Describe the monkey's actions now: <textarea id="write3" rows="2" style="width:100%"></textarea></div>
                <div class="subtask">15.4 Describe the temple (facts): <textarea id="write4" rows="2" style="width:100%"></textarea></div>
                <div class="subtask">15.5 What is happening now in the jungle? (5 sentences): <textarea id="write5" rows="3" style="width:100%"></textarea></div>
                <button class="btn-small" id="saveWritingBtn">Сохранить все ответы</button>
                <div id="task15Feedback" class="feedback"></div>
            </div>
            
            <div id="savedPanel" class="saved-panel no-print" style="display:none;"><i class="fas fa-check-circle"></i> <strong>Все ответы сохранены!</strong></div>
        </div>
        <div class="footer"><i class="fas fa-language"></i> A2+ English | Present Simple vs Present Continuous | 15 заданий (4-5 пунктов каждое)</div>
    </div>
</div>

<script>
    // Vocabulary
    const vocab = [
        { word: "explorer", icon: "🧭", meaning: "исследователь" },
        { word: "jungle", icon: "🌴", meaning: "джунгли" },
        { word: "temple", icon: "🏛️", meaning: "храм" },
        { word: "crystal", icon: "🔮", meaning: "кристалл" },
        { word: "treasure", icon: "💎", meaning: "сокровище" }
    ];
    const vg = document.getElementById('vocabGrid');
    vocab.forEach(v => {
        let c = document.createElement('div'); c.className = 'vocab-card';
        c.innerHTML = <div class="vocab-icon">${v.icon}</div><div class="vocab-word">${v.word}</div><div class="vocab-meaning">${v.meaning}</div>;
        c.onclick = () => { let u = new SpeechSynthesisUtterance(v.word); u.lang = 'en-US'; window.speechSynthesis.cancel(); window.speechSynthesis.speak(u); };
        vg.appendChild(c);
    });
    
    // Story audio
    document.querySelectorAll('.ps-highlight, .pc-highlight').forEach(el => {
        el.onclick = () => { let u = new SpeechSynthesisUtterance(el.innerText); u.lang = 'en-US'; window.speechSynthesis.cancel(); window.speechSynthesis.speak(u); };
    });
    
    // Task 1 check
    document.getElementById('checkTask1').onclick = () => {
        let s = 0;
        if(document.getElementById('q1_1').value === 'correct') s++;
        if(document.getElementById('q1_2').value === 'correct') s++;
        if(document.getElementById('q1_3').value === 'correct') s++;
        if(document.getElementById('q1_4').value === 'correct') s++;
        if(document.getElementById('q1_5').value === 'correct') s++;
        document.getElementById('task1Feedback').innerHTML = <span class="${s===5?'correct':'wrong'}">${s}/5 correct. ${s===5?'Excellent vocabulary!':'Review the words.'}</span>;
    };
    
    // Task 3 check
    document.getElementById('checkTask3').onclick = () => {
        let s = 0;
        if(document.getElementById('q3_1').value === 'correct') s++;
        if(document.getElementById('q3_2').value === 'correct') s++;
        if(document.getElementById('q3_3').value === 'correct') s++;
        if(document.getElementById('q3_4').value === 'correct') s++;
        if(document.getElementById('q3_5').value === 'correct') s++;
        document.getElementById('task3Feedback').innerHTML = <span class="${s===5?'correct':'wrong'}">${s}/5 correct. ${s===5?'Great grammar knowledge!':'Review Present Simple vs Continuous.'}</span>;
    };
    
    // Task 4 check
    document.getElementById('checkTask4').onclick = () => {
        let s = 0;
        if(document.getElementById('q4_1').value === 'correct') s++;
        if(document.getElementById('q4_2').value === 'correct') s++;
        if(document.getElementById('q4_3').value === 'correct') s++;
        if(document.getElementById('q4_4').value === 'correct') s++;
        if(document.getElementById('q4_5').value === 'correct') s++;
        document.getElementById('task4Feedback').innerHTML = <span class="${s===5?'correct':'wrong'}">${s}/5 correct. ${s===5?'Perfect!':'Remember: always/every day/usually = Simple; now/at the moment = Continuous'}</span>;
    };
    
    // Task 5 check
    const tfAnswers = { tf1: 'true', tf2: 'true', tf3: 'true', tf4: 'true', tf5: 'true' };
    ['tf1','tf2','tf3','tf4','tf5'].forEach(id => {
        document.getElementById(id).onchange = () => {
            let val = document.getElementById(id).value;
            let fb = document.getElementById(id+'fb');
            if(val === tfAnswers[id]) fb.innerHTML = '✓';
            else if(val !== '--') fb.innerHTML = '✗';
            else fb.innerHTML = '';
        };
    });
    
    // Task 6 check
    const mcAnswers = { mc1: 'correct', mc2: 'correct', mc3: 'correct', mc4: 'correct', mc5: 'correct' };
    Object.keys(mcAnswers).forEach(id => {
        document.getElementById(id).onchange = () => {
            let correct = document.getElementById(id).value === mcAnswers[id];
            // feedback handled later
        };
    });
    
    // Task 7 check
    document.getElementById('checkTask7').onclick = () => {
        let pcExamples = ['is exploring','is following','is making','is searching','am looking','is pointing','am not dreaming','is taking','is planning'];
        let count = 0;
        for(let i=1; i<=5; i++) {
            let val = document.getElementById(`pc${i}`).value.toLowerCase();
            if(pcExamples.some(ex => val.includes(ex))) count++;
        }
        document.getElementById('task7Feedback').innerHTML = <span class="${count>=3?'correct':'wrong'}">Found ${count}/5 good examples. Examples: is exploring, is following, is pointing, is taking, is planning.</span>;
    };
    
    // Task 8 check
    document.getElementById('checkTask8').onclick = () => {
        let psExamples = ['works','wakes up','checks','thinks','stays','sees','shouts','appears','watches','knows','whispers','touches','opens','shines','glows','sits','understands','is'];
        let count = 0;
        for(let i=1; i<=5; i++) {
            let val = document.getElementById(`ps${i}`).value.toLowerCase();
            if(psExamples.some(ex => val.includes(ex))) count++;
        }
        document.getElementById('task8Feedback').innerHTML = <span class="${count>=3?'correct':'wrong'}">Found ${count}/5 good examples. Examples: works, wakes up, sees, knows, opens, shines.</span>;
    };
    
    // Task 9 check
    document.getElementById('checkTask9').onclick = () => {
        let g1 = document.getElementById('gap1').value.toLowerCase();
        let g2 = document.getElementById('gap2').value.toLowerCase();
        let g3 = document.getElementById('gap3').value.toLowerCase();
        let g4 = document.getElementById('gap4').value.toLowerCase();
        let g5 = document.getElementById('gap5').value.toLowerCase();
        let correct = (g1.includes('works') && g2.includes('is exploring') && g3.includes('is pointing') && (g4.includes('glows')||g4.includes('is glowing')) && g5.includes('are taking'));
        document.getElementById('task9Feedback').innerHTML = <span class="${correct?'correct':'wrong'}">${correct?'✓ All correct! Answers: works, is exploring, is pointing, glows/is glowing, are taking.
':'✗ Check your answers: 1) works, 2) is exploring, 3) is pointing, 4) glows, 5) are taking'}</span>;
    };
    
    // Task 10 check
    document.getElementById('checkTask10').onclick = () => {
        let answers = ['he is taking','she goes','they are playing','the sun rises','i am working'];
        let correct = true;
        for(let i=1; i<=5; i++) {
            let val = document.getElementById(`err${i}`).value.toLowerCase();
            if(!val.includes(answers[i-1])) correct = false;
        }
        document.getElementById('task10Feedback').innerHTML = <span class="${correct?'correct':'wrong'}">${correct?'✓ All corrections correct!':'✗ Correct answers: 1) He is taking photos, 2) She goes to school, 3) They are playing, 4) The sun rises, 5) I am working'}</span>;
    };
    
    // Task 11 check
    document.getElementById('checkTask11').onclick = () => {
        let s = 0;
        if(document.getElementById('char1').value === 'correct') s++;
        if(document.getElementById('char2').value === 'correct') s++;
        if(document.getElementById('char3').value === 'correct') s++;
        if(document.getElementById('char4').value === 'correct') s++;
        if(document.getElementById('char5').value === 'correct') s++;
        document.getElementById('task11Feedback').innerHTML = <span class="${s===5?'correct':'wrong'}">${s}/5 correct. ${s===5?'Perfect character matching!':'Review the story.'}</span>;
    };
    
    // Task 12 check
    document.getElementById('checkTask12').onclick = () => {
        let s = 0;
        for(let i=1; i<=5; i++) if(document.getElementById(`time${i}`).value === 'correct') s++;
        document.getElementById('task12Feedback').innerHTML = <span class="${s===5?'correct':'wrong'}">${s}/5 correct. ${s===5?'Great!':'Now=Continuous, every day=Simple, at the moment=Continuous, often=Simple, Look!=Continuous'}</span>;
    };
    
    // Task 13 check
    document.getElementById('checkTask13').onclick = () => {
        let hasAll = true;
        for(let i=1; i<=5; i++) if(document.getElementById(`create${i}`).value.length < 5) hasAll = false;
        document.getElementById('task13Feedback').innerHTML = <span class="${hasAll?'correct':'wrong'}">${hasAll?'✓ All sentences created! Good job!':'✗ Please complete all 5 sentences.'}</span>;
    };
    
    // Task 14 check
    document.getElementById('checkTask14').onclick = () => {
        let s = 0;
        if(document.getElementById('verb1').value === 'glows' || document.getElementById('verb1').value === 'is glowing') s++;
        if(document.getElementById('verb2').value === 'is looking') s++;
        if(document.getElementById('verb3').value === 'drinks') s++;
        if(document.getElementById('verb4').value === 'are taking') s++;
        if(document.getElementById('verb5').value === 'rises') s++;
        document.getElementById('task14Feedback').innerHTML = <span class="${s===5?'correct':'wrong'}">${s}/5 correct. ${s===5?'Perfect verb choices!':'Check: glows/is glowing, is looking, drinks, are taking, rises'}</span>;
    };
    
    // Save all answers
    function saveAllAnswers() {
        const data = {};
        const inputs = document.querySelectorAll('input, textarea, select');
        inputs.forEach(el => { if(el.id) data[el.id] = el.value; });
        localStorage.setItem('a2_full_15tasks_detailed', JSON.stringify(data));
        document.getElementById('savedPanel').style.display = 'block';
        alert('✅ Все 15 заданий сохранены!');
    }
    
    function loadAllAnswers() {
        const saved = localStorage.getItem('a2_full_15tasks_detailed');
        if(saved) {
            const data = JSON.parse(saved);
            Object.keys(data).forEach(key => {
                const el = document.getElementById(key);
                if(el) el.value = data[key];
            });
            alert('📚 Ваши ответы восстановлены!');
            document.getElementById('savedPanel').style.display = 'block';
        } else alert('Нет сохраненных ответов');
    }
    
    document.getElementById('saveAllBtn').onclick = saveAllAnswers;document.getElementById('loadAllBtn').onclick = loadAllAnswers;
    document.getElementById('saveWritingBtn').onclick = saveAllAnswers;
    
    function downloadPDF() { html2pdf().set({ margin: [0.5,0.5,0.5,0.5], filename: 'English_A2_15tasks.pdf', image: { type: 'jpeg', quality: 0.98 }, html2canvas: { scale: 2 }, jsPDF: { unit: 'in', format: 'a4' } }).from(document.getElementById('lessonToExport')).save(); }
    function saveAsHTML() { let html = document.documentElement.outerHTML; let blob = new Blob([html], {type: 'text/html'}); let a = document.createElement('a'); a.href = URL.createObjectURL(blob); a.download = 'english_a2_15tasks.html'; a.click(); URL.revokeObjectURL(a.href); }
    document.getElementById('downloadPdfBtn').onclick = downloadPDF;
    document.getElementById('saveHtmlBtn').onclick = saveAsHTML;
    
    loadAllAnswers();
</script>
</body>
</html>
