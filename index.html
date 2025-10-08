<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Connectivity Checker</title>
<link rel="icon" href="https://i.ibb.co/W48rv8hd/icon.png" type="image/png">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #75ba1a;
            --secondary: #fb0088;
            --danger: #fb0088;
            --success: #75ba1a;
            --warning: #ff9800;
            --light: #FFFFFF;
            --dark: #292929;
            --bg: #F7F7F7;
            --border: #e0e0e0;
            --highlight: #ffd6e7;
            --text: #333333;
            --card-bg: #FFFFFF;
            --table-header-bg: rgba(117,186,26,0.1);
            --table-row-bg: #FFFFFF;
            --open-color: #75ba1a;
            --closed-color: #fb0088;
            --pending-color: #ff9800;
            --filter-open-bg: rgba(117,186,26,0.2);
            --filter-closed-bg: rgba(251,0,136,0.2);
            --filter-all-bg: rgba(189,189,189,0.2);
            --copy-flash: rgba(117,186,26,0.4);
        }

        .dark-mode {
            --primary: #75ba1a;
            --secondary: #fb0088;
            --danger: #fb0088;
            --success: #75ba1a;
            --warning: #ff9800;
            --light: #1a1a1a;
            --dark: #e0e0e0;
            --bg: #121212;
            --border: #333333;
            --highlight: #4a222f;
            --text: #e0e0e0;
            --card-bg: #1e1e1e;
            --table-header-bg: rgba(117,186,26,0.2);
            --table-row-bg: #252525;
            --open-color: #75ba1a;
            --closed-color: #fb0088;
            --pending-color: #ff9800;
            --filter-open-bg: rgba(117,186,26,0.4);
            --filter-closed-bg: rgba(251,0,136,0.4);
            --filter-all-bg: rgba(189,189,189,0.4);
            --copy-flash: rgba(117,186,26,0.6);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
        }

        body {
            background-color: var(--bg);
            color: var(--text);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 2rem;
            transition: all 0.3s ease;
        }

        .header {
            text-align: center;
            margin-bottom: 2rem;
            width: 100%;
            max-width: 1400px;
        }

        .header h1 {
            color: var(--primary);
            font-size: 2.2rem;
            margin-bottom: 0.5rem;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .header p {
            color: var(--text);
            opacity: 0.8;
            font-size: 1rem;
        }

        .tool-container {
            background: var(--card-bg);
            border-radius: 12px;
            padding: 2rem;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            width: 100%;
            max-width: 1400px;
            border: 1px solid var(--border);
            transition: all 0.3s ease;
            display: flex;
            flex-direction: column;
            gap: 1.5rem;
        }

        .input-section {
            display: flex;
            gap: 2rem;
            margin-bottom: 0;
        }

        .input-box {
            flex: 1;
            min-width: 300px;
            display: flex;
            flex-direction: column;
            gap: 1rem;
        }

        .input-box h3 {
            margin-bottom: 0.5rem;
            color: var(--dark);
            font-size: 1.1rem;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .paste-container {
            position: relative;
            width: 100%;
            margin-bottom: 0;
            flex: 1;
            display: flex;
            flex-direction: column;
        }

        .paste-area {
            width: 100%;
            min-height: 200px;
            max-height: 00px;
            padding: 1.2rem;
            border: 2px dashed var(--border);
            border-radius: 8px;
            font-family: monospace;
            overflow-y: auto;
            resize: vertical;
            background-color: var(--card-bg);
            color: var(--text);
            transition: all 0.3s ease;
            white-space: pre;
            flex: 1;
        }

        .paste-area:focus {
            outline: none;
            border-color: var(--primary);
            box-shadow: 0 0 0 2px rgba(117, 186, 26, 0.2);
        }

        .paste-icon {
            position: absolute;
            right: 15px;
            top: 15px;
            background: var(--primary);
            color: white;
            padding: 24px 22px;
            border-radius: 6px;
            cursor: pointer;
            transition: all 0.3s;
            font-size: 0.9rem;
            display: flex;
            align-items: center;
            gap: 6px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .paste-icon:hover {
            background: var(--secondary);
            transform: translateY(-1px);
        }

        .toolbar {
            display: flex;
            gap: 2rem;
            margin-top: 1rem;
            flex-wrap: wrap;
        }

        .btn {
            padding: 0.8rem 1.4rem;
            border-radius: 8px;
            font-weight: 500;
            border: none;
            cursor: pointer;
            font-size: 1.3rem;
            transition: all 0.3s;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            flex: 1 1 auto;
            min-width: 140px;
            height: 64px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .btn-primary {
            background: var(--primary);
            color: white;
        }

        .btn-primary:hover {
            background: var(--secondary);
            transform: translateY(-1px);
        }

        .btn-secondary {
            background: var(--border);
            color: var(--text);
        }

        .btn-secondary:hover {
            background: var(--border);
            opacity: 0.8;
            transform: translateY(-1px);
        }

        .btn-danger {
            background: var(--danger);
            color: white;
        }

        .btn-danger:hover {
            background: #d33426;
            transform: translateY(-1px);
        }

        .btn-success {
            background: var(--success);
            color: white;
        }

        .btn-success:hover {
            background: #5aa116;
            transform: translateY(-1px);
        }

        .btn-warning {
            background: var(--warning);
            color: white;
        }

        .btn-warning:hover {
            background: #e68a00;
            transform: translateY(-1px);
        }

        table {
            border-collapse: collapse;
            width: 100%;
            margin-top: 1rem;
            table-layout: fixed;
            font-size: 0.9rem;
        }

        th, td {
            border: 1px solid var(--border);
            padding: 0.6rem;
            text-align: left;
            min-width: 100px;
            word-wrap: break-word;
        }

        th {
            background-color: var(--table-header-bg);
            position: sticky;
            top: 0;
            color: var(--text);
            font-size: 0.9rem;
            font-weight: 600;
        }

        td {
            background-color: var(--table-row-bg);
            color: var(--text);
        }

        .open-status {
            background-color: rgba(117,186,26,0.2);
            font-weight: 600;
            color: var(--open-color);
        }

        .closed-status {
            background-color: rgba(251,0,136,0.2);
            font-weight: 600;
            color: var(--closed-color);
        }

        .pending-status {
            background-color: rgba(255,152,0,0.2);
            font-weight: 600;
            color: var(--pending-color);
        }

        .copy-tick {
            position: absolute;
            right: 0px;
            top: 0px;
            background-color: rgba(0,0,0,0.5);
            border-radius: 100%;
            padding: 4px;
            color: white;
            display: none;
        }

        .btn-with-tick {
            position: relative;
        }

        .stats-container {
            background-color: var(--highlight);
            padding: 1rem;
            border-radius: 8px;
            margin: 1rem 0;
            display: none;
            font-size: 0.9rem;
        }

        .stats-row {
            display: flex;
            margin-bottom: 0.5rem;
            align-items: baseline;
        }

        .stats-label {
            flex: 1;
            color: var(--text);
        }

        .stats-value {
            font-weight: bold;
            margin-left: 10px;
            color: var(--text);
        }

        footer {
            margin-top: 3rem;
            text-align: center;
            color: var(--text);
            opacity: 0.7;
            font-size: 0.9rem;
            width: 100%;
            max-width: 1400px;
        }

        .theme-toggle {
            position: fixed;
            top: 20px;
            right: 20px;
            background: var(--primary);
            color: white;
            border: none;
            border-radius: 50%;
            width: 44px;
            height: 44px;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            z-index: 100;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
            font-size: 1.1rem;
            transition: all 0.3s;
        }

        .theme-toggle:hover {
            transform: scale(1.1);
        }

        .output-toolbar {
            display: flex;
            flex-direction: column;
            gap: 3.5rem;
            margin-top: 1.5rem;
        }

        .filter-buttons {
            display: flex;
            gap: 11rem;
            flex-wrap: wrap;
        }

        .filter-btn {
            padding: 0.7rem 1.2rem;
            border-radius: 20px;
            font-weight: 500;
            border: none;
            cursor: pointer;
            font-size: 0.9rem;
            transition: all 0.3s;
            flex: 1 1 auto;
            min-width: 120px;
        }

        .filter-btn.active {
            transform: scale(1.05);
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }

        .filter-all {
            background-color: var(--filter-all-bg);
            color: var(--text);
        }

        .filter-open {
            background-color: var(--filter-open-bg);
            color: var(--open-color);
        }

        .filter-closed {
            background-color: var(--filter-closed-bg);
            color: var(--closed-color);
        }

        .copy-buttons {
            display: flex;
            gap: 5rem;
            flex-wrap: wrap;
            justify-content: flex-end;
        }

        .counter {
            background-color: var(--highlight);
            padding: 1.2rem;
            border-radius: 8px;
            margin: 1rem 0;
            font-size: 0.95rem;
            display: none;
        }

        .counter-row {
            display: flex;
            margin-bottom: 0.6rem;
        }

        .counter-label {
            flex: 1;
            color: var(--text);
            font-size: 0.95rem;
        }

        .counter-value {
            font-weight: bold;
            margin-left: 10px;
            color: var(--text);
            font-size: 0.95rem;
        }

                .copy-status {
            margin: 0.5rem 0;
            padding: 0.8rem;
            text-align: center;
            font-size: 0.95rem;
            color: black;
            background-color: rgba(255, 214, 231, 0.2); /* 20% transparent highlight */
            border-radius: 6px;
            border-left: 4px solid var(--secondary);
            font-weight: 500;
        }

        .copy-status.copied {
            background-color: rgba(117, 186, 26, 0.2); /* 20% transparent green */
            color: var(--text);
        }

        .copy-status.error {
            background-color: rgba(251, 0, 136, 0.2); /* 20% transparent pink */
            color: var(--text);
        }

        .current-copy {
            background-color: var(--copy-flash);
            transition: background-color 0.5s ease-out;
        }

        .modal {
            display: none;
            position: fixed;
            z-index: 1000;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.5);
        }

        .modal-content {
            background-color: var(--card-bg);
            margin: 10% auto;
            padding: 1.8rem;
            border: 1px solid var(--border);
            border-radius: 8px;
            width: 90%;
            max-width: 600px;
            max-height: 80vh;
            overflow-y: auto;
        }

        .modal-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 1.5rem;
        }

        .modal-header h2 {
            color: var(--primary);
            font-size: 1.5rem;
        }

        .close {
            color: var(--text);
            font-size: 28px;
            font-weight: bold;
            cursor: pointer;
        }

        .close:hover {
            color: var(--danger);
        }

        .modal-body {
            margin-bottom: 1.5rem;
        }

        .modal-footer {
            display: flex;
            justify-content: flex-end;
            gap: 1rem;
        }

        @media (min-width: 1200px) {
            .tool-container {
                padding: 2.5rem;
            }
            
            .input-section {
                gap: 2.5rem;
            }
            
            .paste-area {
                min-height: 250px;
            }
            
            .btn {
                padding: 0.9rem 1.5rem;
                font-size: 1rem;
            }
        }

        @media (max-width: 768px) {
            body {
                padding: 1.5rem;
            }
            
            .header h1 {
                font-size: 1.8rem;
            }
            
            .tool-container {
                padding: 1.5rem;
            }
            
            .input-section {
                flex-direction: column;
                gap: 1.5rem;
            }
            
            .toolbar {
                flex-direction: column;
            }
            
            .btn {
                width: 100%;
            }
            
            .filter-buttons, .copy-buttons {
                flex-direction: column;
            }
            
            .filter-btn, .btn-with-tick {
                width: 100%;
            }
            
            .output-toolbar {
                gap: 1rem;
            }
        }
    </style>
</head>
<body>
    <button class="theme-toggle" id="themeToggle">
        <i class="fas fa-moon"></i>
    </button>

    <div class="header">
        <h1><i class="fas fa-plug"></i> Connectivity Checker</h1>
        <p>Check which numbers are open or closed!</p>
    </div>

    <div class="tool-container">
        <div class="input-section">
            <div class="input-box">
                <h3><i class="fas fa-database"></i> CC Record Data</h3>
                <div class="paste-container">
                    <div class="paste-area" id="ccDataArea" contenteditable="true" placeholder="Paste your CC record data here..."></div>
                    <div class="paste-icon" onclick="pasteData('ccDataArea')">
                        <i class="fas fa-paste"></i> Paste
                    </div>
                </div>
                <div class="toolbar">
                    <button class="btn btn-primary" onclick="processCCData()">
                        <i class="fas fa-cogs"></i> Process
                    </button>
                    <button class="btn btn-danger" onclick="clearCCData()">
                        <i class="fas fa-trash-alt"></i> Clear
                    </button>
                    <button class="btn btn-secondary" onclick="showEditOBIDsModal()">
                        <i class="fas fa-edit"></i> Edit OB IDs
                    </button>
                </div>
            </div>
        </div>

        <div class="toolbar">
            <button class="btn btn-success" onclick="showAddScrapModal()">
                <i class="fas fa-plus"></i> Add Scrap
            </button>
            <button class="btn btn-warning" onclick="addLeadingZeros()">
                <i class="fas fa-plus-circle"></i> Add Zeros
            </button>
        </div>

        <div id="counter" class="counter">
            <div class="counter-row">
                <span class="counter-label">Current Position:</span>
                <span class="counter-value" id="currentPosition">0</span>
            </div>
            <div class="counter-row">
                <span class="counter-label">Total Numbers:</span>
                <span class="counter-value" id="totalNumbers">0</span>
            </div>
            <div class="counter-row">
                <span class="counter-label">Open Numbers:</span>
                <span class="counter-value" id="openNumbers">0</span>
            </div>
            <div class="counter-row">
                <span class="counter-label">Closed Numbers:</span>
                <span class="counter-value" id="closedNumbers">0</span>
            </div>
        </div>

        <div class="copy-status" id="copyStatus">Ready</div>

        <div class="output-section">
            <h3>Results</h3>
            <div class="output-toolbar">
                <div class="filter-buttons">
                    <button class="filter-btn filter-all active" onclick="filterTable('all')">Show All</button>
                    <button class="filter-btn filter-open" onclick="filterTable('open')">Show Open Only</button>
                    <button class="filter-btn filter-closed" onclick="filterTable('closed')">Show Closed Only</button>
                </div>
                <div class="copy-buttons">
                    <button class="btn btn-primary btn-with-tick" onclick="copyAllData()">
                        <i class="fas fa-copy"></i> Copy All
                        <span class="copy-tick"><i class="fas fa-check"></i></span>
                    </button>
                    <button class="btn btn-success btn-with-tick" onclick="copyNextNumber()">
                        <i class="fas fa-arrow-right"></i> Copy Next (#<span id="nextNumberIndex">0</span>)
                        <span class="copy-tick"><i class="fas fa-check"></i></span>
                    </button>
                    <button class="btn btn-secondary btn-with-tick" onclick="copyPreviousNumber()">
                        <i class="fas fa-arrow-left"></i> Copy Back
                        <span class="copy-tick"><i class="fas fa-check"></i></span>
                    </button>
                    <button class="btn btn-warning btn-with-tick" onclick="startOver()">
                        <i class="fas fa-redo"></i> Start Over
                        <span class="copy-tick"><i class="fas fa-check"></i></span>
                    </button>
                </div>
            </div>
            <div id="tableContainer" style="overflow-x: auto;">
                <table id="dataTable">
                    <thead>
                        <tr>
                            <th>A</th>
                            <th>B</th>
                            <th>C</th>
                            <th>D</th>
                            <th>E</th>
                            <th>F (Status)</th>
                            <th>G (Remarks)</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
                        <tr><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
                        <tr><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
                    </tbody>
                </table>
            </div>
        </div>
    </div>

    <!-- Add Scrap Modal -->
    <div id="addScrapModal" class="modal">
        <div class="modal-content">
            <div class="modal-header">
                <h2>Add Scrap Data</h2>
                <span class="close" onclick="closeAddScrapModal()">&times;</span>
            </div>
            <div class="modal-body">
                <div class="paste-container">
                    <div class="paste-area" id="scrapDataArea" contenteditable="true" placeholder="Paste your scrap data here..."></div>
                    <div class="paste-icon" onclick="pasteData('scrapDataArea')">
                        <i class="fas fa-paste"></i> Paste
                    </div>
                </div>
            </div>
            <div class="modal-footer">
                <button class="btn btn-secondary" onclick="closeAddScrapModal()">
                    <i class="fas fa-times"></i> Cancel
                </button>
                <button class="btn btn-primary" onclick="addScrapData()">
                    <i class="fas fa-plus"></i> Add
                </button>
            </div>
        </div>
    </div>

    <!-- Edit OB IDs Modal -->
    <div id="editOBIDsModal" class="modal">
        <div class="modal-content">
            <div class="modal-header">
                <h2>Edit OB Agent IDs</h2>
                <span class="close" onclick="closeEditOBIDsModal()">&times;</span>
            </div>
            <div class="modal-body">
                <div class="paste-container">
                    <div class="paste-area" id="obIDsArea" contenteditable="true" placeholder="Enter OB Agent IDs, one per line..."></div>
                </div>
                <p style="margin-top: 10px; font-size: 0.8rem; color: var(--text); opacity: 0.7;">
                    These IDs will be used to determine if a number is "Closed" (when agent ID is found) or "Open" (when no agent ID is found).
                </p>
            </div>
            <div class="modal-footer">
                <button class="btn btn-secondary" onclick="resetDefaultOBIDs()">
                    <i class="fas fa-undo"></i> Reset Default
                </button>
                <button class="btn btn-danger" onclick="closeEditOBIDsModal()">
                    <i class="fas fa-times"></i> Cancel
                </button>
                <button class="btn btn-primary" onclick="saveOBIDs()">
                    <i class="fas fa-save"></i> Save
                </button>
            </div>
        </div>
    </div>

    <footer>
        © Workflow Tools 2025 | Data is processed in your browser only (not saved to server)
    </footer>

    <script>
        // Store processed data for later use
        let scrapData = [];
        let currentIndex = 0;
        let obAgentIDs = new Set([
            // Default OB Agent IDs
            46857, 10949, 4295, 45668, 45720, 11099, 44715, 48343, 46973, 54884, 2743, 48618, 48641, 48152, 45403, 2323, 
            48646, 4826, 11911, 44372, 4900, 47923, 47455, 48587, 54888, 3239, 2680, 48883, 47856, 46238, 48882, 46771, 
            48362, 44799, 48036, 48375, 44761, 47792, 44457, 48872, 46088, 48126, 2697, 43942, 43207, 46288, 43406, 48396, 
            2101, 54871, 48664, 48932, 48606, 2593, 11488, 44374, 2413, 43365, 44312, 46487, 42234, 48122, 43647, 45470, 
            11929, 45863, 2547, 46958, 11475, 46779, 48623, 47104, 47100, 48614, 43075, 48277, 44512, 43393, 42113, 45964, 
            46633, 48346, 42482, 3011, 44790, 2453, 42141, 2681, 2225, 43171, 49026, 48265, 48805, 46871, 46543, 46019, 
            42071, 47850, 3024, 2726, 11407, 3070, 46602, 54872, 48594, 2434, 48284, 45910, 3091, 46976, 46002, 48795, 
            47829, 48048, 11797, 44836, 5675, 48808, 44551, 48297, 44877, 4790, 47838, 46067, 2267, 49091, 48342, 42002, 
            6364, 48796, 45779, 48313, 6058, 48215, 2282, 48609, 46854, 44619, 48120, 45878, 42500, 3346, 49128, 42036, 
            4937, 46654, 43930, 45474, 54883, 43810, 48777, 48197, 11888, 46450, 43760, 43272, 49130, 45658, 48865, 48133, 
            42219, 46849, 54870, 48972, 48925, 46837, 48368, 48886, 47934, 48638, 49047, 49133, 43374, 42856, 47916, 46366, 
            46291, 44000, 48690, 44041, 45000, 47878, 44080, 44015, 2706, 48616, 49145, 48046, 46931, 46641, 48665, 49112, 
            48642, 46966, 6050, 47449, 45833, 46877, 48387, 48931, 49111, 48739, 45570, 44788, 45670, 48417, 45545, 2800, 
            48671, 48801, 4448, 48354, 47750, 46936, 43856, 2942, 3932, 47786, 48586, 48870, 42006, 44144, 4002, 48800, 
            48667, 44688, 2846, 3330, 45854, 48194, 3143, 49152, 49029, 42265, 3231, 45673, 48052, 48927, 42504, 4355, 
            49123, 48153, 42046, 2946, 48621, 43593, 48988, 44545, 45660, 48813, 48659, 48033, 4048, 45401, 46466, 42009, 
            48328, 48949, 3054, 49052, 49021, 48878, 2284, 48863, 46962, 49076, 45461, 46824, 48896, 45980, 44554, 48906, 
            48745, 4385, 43874, 44699, 44115, 48652, 48971, 43713, 4037, 48975, 3903, 49002, 42172, 49088, 49087, 2919, 
            44184, 48011, 48706, 48137, 48034, 48803, 48910, 47393, 46770, 47855, 3167, 48504, 48781, 48729, 47075, 48992, 
            45913, 4500, 42003, 48890, 46681, 48741, 4696, 47742, 44188, 47961, 47487, 48676, 47950, 49134, 48718, 48782, 
            46693, 4945, 43753, 2763, 47427, 3710, 49120, 48981, 11848, 48054, 48394, 48864, 3025, 54895, 49043, 2902, 
            48383, 46471, 49151, 48709, 48163, 48151, 48941, 2755, 49044, 3009, 49146, 46923, 45880, 48854, 47745, 49110, 
            44169, 4276, 43048, 49006, 44156, 48708, 48702, 48884, 46457, 49031, 49142, 4386, 49109, 43304, 49041, 2868, 
            49025, 49007, 47754, 44862, 49045, 48207, 47125, 45992, 49141, 43147, 49046, 5991, 46772, 4882, 49147, 48982, 
            48268, 47788, 48135, 45807, 47784, 46875, 48836, 46872, 42087, 45879, 44472, 43319, 48900, 48688, 43395, 46351, 
            49140, 49154, 48802, 6042, 48902, 49099, 49080, 48668, 2723, 48697, 48682, 48978, 48123, 47079, 49093, 48707, 
            49129, 49150, 49137, 48714, 49079, 48156, 48833, 46093, 48711, 48851, 43625, 48898, 49034, 48689, 49138, 48698, 
            49105, 48935, 49102, 49020, 49148, 48936, 47207, 49032, 48627, 48282, 49040, 47230, 48380
        ]);
        let isDarkMode = false;
        let currentFilter = 'all';

        document.addEventListener('DOMContentLoaded', function() {
            // Load saved OB Agent IDs from localStorage if available
            const savedOBIDs = localStorage.getItem('obAgentIDs');
            if (savedOBIDs) {
                obAgentIDs = new Set(JSON.parse(savedOBIDs));
            }
            
            // Check for saved theme preference
            if (localStorage.getItem('darkMode') === 'enabled') {
                enableDarkMode();
            }

            // Add keyboard shortcuts
            document.addEventListener('keydown', function(e) {
                // Ctrl+Enter for Copy Next
                if (e.ctrlKey && e.key === 'Enter') {
                    e.preventDefault();
                    copyNextNumber();
                }
                
                // Ctrl+Backspace for Copy Back
                if (e.ctrlKey && e.key === 'Backspace') {
                    e.preventDefault();
                    copyPreviousNumber();
                }
                
                // Ctrl+Shift+Enter for Start Over
                if (e.ctrlKey && e.shiftKey && e.key === 'Enter') {
                    e.preventDefault();
                    startOver();
                }
            });
        });

        // Theme toggle functionality
        document.getElementById('themeToggle').addEventListener('click', function() {
            isDarkMode = !isDarkMode;
            if (isDarkMode) {
                enableDarkMode();
                localStorage.setItem('darkMode', 'enabled');
            } else {
                disableDarkMode();
                localStorage.setItem('darkMode', 'disabled');
            }
        });

        function enableDarkMode() {
            document.body.classList.add('dark-mode');
            document.getElementById('themeToggle').innerHTML = '<i class="fas fa-sun"></i>';
            isDarkMode = true;
        }

        function disableDarkMode() {
            document.body.classList.remove('dark-mode');
            document.getElementById('themeToggle').innerHTML = '<i class="fas fa-moon"></i>';
            isDarkMode = false;
        }

        function startOver() {
            currentIndex = 0;
            updateCounter();
            showCopyStatus('Reset to start position', true);
        }

        async function pasteData(areaId) {
            try {
                const clipboardItems = await navigator.clipboard.read();
                for (const clipboardItem of clipboardItems) {
                    for (const type of clipboardItem.types) {
                        if (type === 'text/plain') {
                            const blob = await clipboardItem.getType(type);
                            const text = await blob.text();
                            
                            // Get current selection/cursor position
                            const pasteArea = document.getElementById(areaId);
                            const selection = window.getSelection();
                            const currentText = pasteArea.textContent;
                            
                            // Add separator if there's existing content
                            const separator = currentText && !currentText.endsWith('\n') ? '\n' : '';
                            
                            if (!selection.isCollapsed) {
                                // Replace selection
                                const range = selection.getRangeAt(0);
                                range.deleteContents();
                                range.insertNode(document.createTextNode(separator + text));
                            } else {
                                // Append at cursor
                                const cursorPos = selection.anchorOffset;
                                pasteArea.textContent = currentText.slice(0, cursorPos) + separator + text + currentText.slice(cursorPos);
                            }
                            
                            // Move cursor to end of pasted content
                            const range = document.createRange();
                            range.selectNodeContents(pasteArea);
                            range.collapse(false);
                            selection.removeAllRanges();
                            selection.addRange(range);
                            
                            return;
                        }
                    }
                }
                showCopyStatus('No text data found in clipboard', false);
            } catch (err) {
                console.error('Failed to read clipboard:', err);
                document.getElementById(areaId).focus();
                showCopyStatus('Please use Ctrl+V to paste your data into the input box', false);
            }
        }

        // Normalize phone numbers by removing all non-digit characters
        function normalizePhoneNumber(phone) {
            if (!phone) return '';
            // Remove all non-digit characters
            return phone.replace(/\D/g, '');
        }

        function showAddScrapModal() {
            document.getElementById('addScrapModal').style.display = 'block';
            document.getElementById('scrapDataArea').focus();
        }

        function closeAddScrapModal() {
            document.getElementById('addScrapModal').style.display = 'none';
        }

        function addScrapData() {
            const scrapDataText = document.getElementById('scrapDataArea').textContent.trim();
            
            if (!scrapDataText) {
                showCopyStatus('Please paste scrap data before adding', false);
                return;
            }

            // Parse scrap data (tab-separated columns)
            const scrapRows = scrapDataText.split(/\r\n|\n|\r/).filter(row => row.trim() !== '');
            
            scrapData = scrapRows.map(row => {
                const columns = row.split(/\t/);
                let phoneNumber = columns[0] ? columns[0].trim() : '';
                
                return {
                    columns: columns,
                    number: phoneNumber,
                    normalizedNumber: normalizePhoneNumber(phoneNumber),
                    status: 'Pending',
                    remarks: 'Not processed yet'
                };
            });

            // Reset current index
            currentIndex = 0;
            
            // Render the table
            renderTable(scrapData);
            
            // Update counter
            updateCounter();
            
            // Show counter
            document.getElementById('counter').style.display = 'block';
            
            // Close the modal and clear the textarea
            closeAddScrapModal();
            document.getElementById('scrapDataArea').textContent = '';
            
            showCopyStatus(`Added ${scrapData.length} numbers from scrap data`, true);
        }

        function addLeadingZeros() {
            if (scrapData.length === 0) {
                showCopyStatus('No scrap data to process. Please add scrap data first.', false);
                return;
            }
            
            let modifiedCount = 0;
            
            scrapData.forEach(item => {
                // Check if the number is missing leading zero (Pakistan number pattern)
                const normalized = normalizePhoneNumber(item.number);
                if (/^3\d{9}$/.test(normalized)) {
                    item.number = '0' + normalized;
                    item.normalizedNumber = normalized;
                    modifiedCount++;
                } else if (/^\d{10}$/.test(normalized)) {
                    item.normalizedNumber = normalized;
                }
            });
            
            if (modifiedCount > 0) {
                renderTable(scrapData);
                showCopyStatus(`Added leading zeros to ${modifiedCount} numbers`, true);
            } else {
                showCopyStatus('No numbers needed leading zeros added', true);
            }
        }

        function processCCData() {
            const ccDataText = document.getElementById('ccDataArea').textContent.trim();
            
            if (!ccDataText) {
                showCopyStatus('Please paste CC record data before processing', false);
                return;
            }

            if (scrapData.length === 0) {
                showCopyStatus('Please add scrap data first', false);
                return;
            }

            // Parse CC data to extract phone numbers and staff IDs
            const ccRows = ccDataText.split(/\r\n|\n|\r/).filter(row => row.trim() !== '');
            
            let processedCount = 0;
            
            // Process each CC record
            ccRows.forEach(row => {
                const columns = row.split(/\t/);
                
                // Try to find phone number in column G (index 6) or similar
                let phoneNumber = '';
                if (columns.length >= 7) {
                    phoneNumber = normalizePhoneNumber(columns[6]);
                } else {
                    // If not enough columns, try to find any phone number in the row
                    const phoneMatch = row.match(/\b\d{10,11}\b/);
                    if (phoneMatch) phoneNumber = normalizePhoneNumber(phoneMatch[0]);
                }
                
                if (!phoneNumber) return;
                
                // Try to find staff ID in column O (index 14) or similar
                let staffId = null;
                if (columns.length >= 15) {
                    const idMatch = columns[14].match(/\b\d{4,5}\b/);
                    if (idMatch) staffId = parseInt(idMatch[0]);
                } else {
                    // If not enough columns, try to find any ID in the row
                    const idMatch = row.match(/\b\d{4,5}\b/);
                    if (idMatch) staffId = parseInt(idMatch[0]);
                }
                
                // Find matching scrap data item
                const matchingItem = scrapData.find(item => 
                    item.normalizedNumber === phoneNumber || 
                    phoneNumber.includes(item.normalizedNumber) || 
                    item.normalizedNumber.includes(phoneNumber)
                );
                
                if (matchingItem) {
                    if (staffId !== null && obAgentIDs.has(staffId)) {
                        matchingItem.status = 'Closed';
                        matchingItem.remarks = `OB Agent ID ${staffId} found`;
                        processedCount++;
                    } else if (matchingItem.status === 'Pending') {
                        matchingItem.status = 'Open';
                        matchingItem.remarks = staffId ? 'No OB Agent ID found' : 'No Staff ID found';
                        processedCount++;
                    }
                }
            });

            // Render the updated table
            renderTable(scrapData);
            
            // Update counter
            updateCounter();
            
            if (processedCount > 0) {
                showCopyStatus(`Updated status for ${processedCount} numbers`, true);
            } else {
                showCopyStatus('No matching numbers found in CC data', false);
            }
        }

        function renderTable(data) {
            const table = document.getElementById('dataTable');
            const tbody = table.querySelector('tbody');
            tbody.innerHTML = '';
            
            if (data.length === 0) {
                // Add empty rows for better UI
                for (let i = 0; i < 3; i++) {
                    const row = document.createElement('tr');
                    for (let j = 0; j < 7; j++) {
                        const td = document.createElement('td');
                        td.innerHTML = '&nbsp;';
                        row.appendChild(td);
                    }
                    tbody.appendChild(row);
                }
                return;
            }
            
            data.forEach((item, index) => {
                // Skip if filtered
                if (currentFilter === 'open' && item.status !== 'Open') return;
                if (currentFilter === 'closed' && item.status !== 'Closed') return;
                
                const row = document.createElement('tr');
                row.dataset.index = index;
                
                // Highlight current copied row
                if (index === currentIndex - 1) {
                    row.classList.add('current-copy');
                    setTimeout(() => {
                        row.classList.remove('current-copy');
                    }, 500);
                }
                
                // Add all columns from scrap data
                for (let i = 0; i < 5 && i < item.columns.length; i++) {
                    const cell = document.createElement('td');
                    cell.textContent = item.columns[i] || '';
                    row.appendChild(cell);
                }
                
                // Add empty cells if there are fewer than 5 columns
                for (let i = item.columns.length; i < 5; i++) {
                    const cell = document.createElement('td');
                    cell.innerHTML = '&nbsp;';
                    row.appendChild(cell);
                }
                
                // Add status cell
                const statusCell = document.createElement('td');
                statusCell.textContent = item.status;
                if (item.status === 'Open') {
                    statusCell.classList.add('open-status');
                } else if (item.status === 'Closed') {
                    statusCell.classList.add('closed-status');
                } else {
                    statusCell.classList.add('pending-status');
                }
                row.appendChild(statusCell);
                
                // Add remarks cell
                const remarksCell = document.createElement('td');
                remarksCell.textContent = item.remarks;
                row.appendChild(remarksCell);
                
                tbody.appendChild(row);
            });
        }

        function filterTable(filter) {
            currentFilter = filter;
            
            // Update active button
            document.querySelectorAll('.filter-btn').forEach(btn => {
                btn.classList.remove('active');
            });
            document.querySelector(`.filter-${filter}`).classList.add('active');
            
            // Re-render table
            renderTable(scrapData);
        }

        function updateCounter() {
            document.getElementById('currentPosition').textContent = currentIndex + 1;
            document.getElementById('totalNumbers').textContent = scrapData.length;
            
            const openCount = scrapData.filter(item => item.status === 'Open').length;
            const closedCount = scrapData.filter(item => item.status === 'Closed').length;
            
            document.getElementById('openNumbers').textContent = openCount;
            document.getElementById('closedNumbers').textContent = closedCount;
            
            // Update next number index
            document.getElementById('nextNumberIndex').textContent = currentIndex + 1;
        }

        function clearCCData() {
            document.getElementById('ccDataArea').textContent = '';
        }

        function copyAllData() {
            if (scrapData.length === 0) {
                showCopyStatus('No data to copy. Please add scrap data first.', false);
                return;
            }
            
            // Filter data based on current filter
            let filteredData = scrapData;
            if (currentFilter === 'open') {
                filteredData = scrapData.filter(item => item.status === 'Open');
            } else if (currentFilter === 'closed') {
                filteredData = scrapData.filter(item => item.status === 'Closed');
            }
            
            // Create CSV-like text with all columns (excluding headers)
            const rows = filteredData.map(item => [
                ...item.columns.slice(0, 5),
                item.status,
                item.remarks
            ]);
            
            // Ensure we have 5 columns for each row
            rows.forEach(row => {
                while (row.length < 5) row.push('');
                row.push(row[5] || ''); // Status
                row.push(row[6] || ''); // Remarks
            });
            
            const csvContent = rows.map(row => row.join('\t')).join('\n');
            
            navigator.clipboard.writeText(csvContent).then(() => {
                const tick = document.querySelector('.output-toolbar .copy-tick');
                tick.style.display = 'inline-block';
                setTimeout(() => {
                    tick.style.display = 'none';
                }, 2000);
                
                showCopyStatus(`Copied ${filteredData.length} items to clipboard (without headers)`, true);
            }).catch(err => {
                console.error('Failed to copy:', err);
                showCopyStatus('Failed to copy data. Please try again.', false);
            });
        }

        function copyNextNumber() {
            if (scrapData.length === 0) {
                showCopyStatus('No data to copy. Please add scrap data first.', false);
                return;
            }
            
            if (currentIndex >= scrapData.length) {
                currentIndex = 0; // Reset to start
            }
            
            const item = scrapData[currentIndex];
            const numberToCopy = item.number;
            
            navigator.clipboard.writeText(numberToCopy).then(() => {
                const tick = document.querySelectorAll('.output-toolbar .copy-tick')[1];
                tick.style.display = 'inline-block';
                setTimeout(() => {
                    tick.style.display = 'none';
                }, 2000);
                
                showCopyStatus(`Copied: ${numberToCopy} (${item.status})`, true);
                
                // Move to next number
                currentIndex++;
                
                // Update counter
                updateCounter();
                
                // Re-render table to show highlight
                renderTable(scrapData);
            }).catch(err => {
                console.error('Failed to copy:', err);
                showCopyStatus('Failed to copy number. Please try again.', false);
            });
        }

        function copyPreviousNumber() {
            if (scrapData.length === 0) {
                showCopyStatus('No data to copy. Please add scrap data first.', false);
                return;
            }
            
            if (currentIndex <= 0) {
                currentIndex = scrapData.length; // Start from end
            }
            
            currentIndex--;
            const item = scrapData[currentIndex];
            const numberToCopy = item.number;
            
            navigator.clipboard.writeText(numberToCopy).then(() => {
                const tick = document.querySelectorAll('.output-toolbar .copy-tick')[2];
                tick.style.display = 'inline-block';
                setTimeout(() => {
                    tick.style.display = 'none';
                }, 2000);
                
                showCopyStatus(`Copied: ${numberToCopy} (${item.status})`, true);
                
                // Update counter
                updateCounter();
                
                // Re-render table to show highlight
                renderTable(scrapData);
            }).catch(err => {
                console.error('Failed to copy:', err);
                showCopyStatus('Failed to copy number. Please try again.', false);
            });
        }

        function showCopyStatus(message, isSuccess) {
            const copyStatus = document.getElementById('copyStatus');
            copyStatus.textContent = message;
            
            if (isSuccess) {
                copyStatus.className = 'copy-status copied';
            } else {
                copyStatus.className = 'copy-status error';
            }
        }

        function showEditOBIDsModal() {
            const modal = document.getElementById('editOBIDsModal');
            const obIDsArea = document.getElementById('obIDsArea');
            
            // Populate the textarea with current OB Agent IDs
            obIDsArea.textContent = Array.from(obAgentIDs).join('\n');
            
            modal.style.display = 'block';
            obIDsArea.focus();
        }

        function closeEditOBIDsModal() {
            document.getElementById('editOBIDsModal').style.display = 'none';
        }

        function resetDefaultOBIDs() {
            // Reset to default OB Agent IDs
            obAgentIDs = new Set([
                46857, 10949, 4295, 45668, 45720, 11099, 44715, 48343, 46973, 54884, 2743, 48618, 48641, 48152, 45403, 2323, 
                48646, 4826, 11911, 44372, 4900, 47923, 47455, 48587, 54888, 3239, 2680, 48883, 47856, 46238, 48882, 46771, 
                48362, 44799, 48036, 48375, 44761, 47792, 44457, 48872, 46088, 48126, 2697, 43942, 43207, 46288, 43406, 48396, 
                2101, 54871, 48664, 48932, 48606, 2593, 11488, 44374, 2413, 43365, 44312, 46487, 42234, 48122, 43647, 45470, 
                11929, 45863, 2547, 46958, 11475, 46779, 48623, 47104, 47100, 48614, 43075, 48277, 44512, 43393, 42113, 45964, 
                46633, 48346, 42482, 3011, 44790, 2453, 42141, 2681, 2225, 43171, 49026, 48265, 48805, 46871, 46543, 46019, 
                42071, 47850, 3024, 2726, 11407, 3070, 46602, 54872, 48594, 2434, 48284, 45910, 3091, 46976, 46002, 48795, 
                47829, 48048, 11797, 44836, 5675, 48808, 44551, 48297, 44877, 4790, 47838, 46067, 2267, 49091, 48342, 42002, 
                6364, 48796, 45779, 48313, 6058, 48215, 2282, 48609, 46854, 44619, 48120, 45878, 42500, 3346, 49128, 42036, 
                4937, 46654, 43930, 45474, 54883, 43810, 48777, 48197, 11888, 46450, 43760, 43272, 49130, 45658, 48865, 48133, 
                42219, 46849, 54870, 48972, 48925, 46837, 48368, 48886, 47934, 48638, 49047, 49133, 43374, 42856, 47916, 46366, 
                46291, 44000, 48690, 44041, 45000, 47878, 44080, 44015, 2706, 48616, 49145, 48046, 46931, 46641, 48665, 49112, 
                48642, 46966, 6050, 47449, 45833, 46877, 48387, 48931, 49111, 48739, 45570, 44788, 45670, 48417, 45545, 2800, 
                48671, 48801, 4448, 48354, 47750, 46936, 43856, 2942, 3932, 47786, 48586, 48870, 42006, 44144, 4002, 48800, 
                48667, 44688, 2846, 3330, 45854, 48194, 3143, 49152, 49029, 42265, 3231, 45673, 48052, 48927, 42504, 4355, 
                49123, 48153, 42046, 2946, 48621, 43593, 48988, 44545, 45660, 48813, 48659, 48033, 4048, 45401, 46466, 42009, 
                48328, 48949, 3054, 49052, 49021, 48878, 2284, 48863, 46962, 49076, 45461, 46824, 48896, 45980, 44554, 48906, 
                48745, 4385, 43874, 44699, 44115, 48652, 48971, 43713, 4037, 48975, 3903, 49002, 42172, 49088, 49087, 2919, 
                44184, 48011, 48706, 48137, 48034, 48803, 48910, 47393, 46770, 47855, 3167, 48504, 48781, 48729, 47075, 48992, 
                45913, 4500, 42003, 48890, 46681, 48741, 4696, 47742, 44188, 47961, 47487, 48676, 47950, 49134, 48718, 48782, 
                46693, 4945, 43753, 2763, 47427, 3710, 49120, 48981, 11848, 48054, 48394, 48864, 3025, 54895, 49043, 2902, 
                48383, 46471, 49151, 48709, 48163, 48151, 48941, 2755, 49044, 3009, 49146, 46923, 45880, 48854, 47745, 49110, 
                44169, 4276, 43048, 49006, 44156, 48708, 48702, 48884, 46457, 49031, 49142, 4386, 49109, 43304, 49041, 2868, 
                49025, 49007, 47754, 44862, 49045, 48207, 47125, 45992, 49141, 43147, 49046, 5991, 46772, 4882, 49147, 48982, 
                48268, 47788, 48135, 45807, 47784, 46875, 48836, 46872, 42087, 45879, 44472, 43319, 48900, 48688, 43395, 46351, 
                49140, 49154, 48802, 6042, 48902, 49099, 49080, 48668, 2723, 48697, 48682, 48978, 48123, 47079, 49093, 48707, 
                49129, 49150, 49137, 48714, 49079, 48156, 48833, 46093, 48711, 48851, 43625, 48898, 49034, 48689, 49138, 48698, 
                49105, 48935, 49102, 49020, 49148, 48936, 47207, 49032, 48627, 48282, 49040, 47230, 48380
            ]);
            
            document.getElementById('obIDsArea').textContent = Array.from(obAgentIDs).join('\n');
            showCopyStatus('Default OB Agent IDs have been restored.', true);
        }

        function saveOBIDs() {
            const obIDsText = document.getElementById('obIDsArea').textContent.trim();
            
            if (!obIDsText) {
                showCopyStatus('Please enter at least one OB Agent ID', false);
                return;
            }
            
            // Parse the IDs (one per line, numeric only)
            const newIDs = obIDsText.split(/\r\n|\n|\r/)
                .map(id => id.trim())
                .filter(id => /^\d+$/.test(id))
                .map(id => parseInt(id));
            
            if (newIDs.length === 0) {
                showCopyStatus('No valid OB Agent IDs found. Please enter numeric IDs only.', false);
                return;
            }
            
            // Update the OB Agent IDs set
            obAgentIDs = new Set(newIDs);
            
            // Save to localStorage
            localStorage.setItem('obAgentIDs', JSON.stringify(Array.from(obAgentIDs)));
            
            closeEditOBIDsModal();
            showCopyStatus(`Saved ${obAgentIDs.size} OB Agent IDs. They will be used for processing.`, true);
        }

        // Handle paste events for text areas
        document.getElementById('ccDataArea').addEventListener('paste', function(e) {
            e.preventDefault();
            const text = (e.clipboardData || window.clipboardData).getData('text');
            const selection = window.getSelection();
            const currentText = this.textContent;
            
            // Add separator if there's existing content
            const separator = currentText && !currentText.endsWith('\n') ? '\n' : '';
            
            if (!selection.isCollapsed) {
                // Replace selection
                const range = selection.getRangeAt(0);
                range.deleteContents();
                range.insertNode(document.createTextNode(separator + text));
            } else {
                // Append at cursor
                const cursorPos = selection.anchorOffset;
                this.textContent = currentText.slice(0, cursorPos) + separator + text + currentText.slice(cursorPos);
            }
            
            // Move cursor to end of pasted content
            const range = document.createRange();
            range.selectNodeContents(this);
            range.collapse(false);
            selection.removeAllRanges();
            selection.addRange(range);
        });
        
        document.getElementById('scrapDataArea').addEventListener('paste', function(e) {
            e.preventDefault();
            const text = (e.clipboardData || window.clipboardData).getData('text');
            const selection = window.getSelection();
            const currentText = this.textContent;
            
            // Add separator if there's existing content
            const separator = currentText && !currentText.endsWith('\n') ? '\n' : '';
            
            if (!selection.isCollapsed) {
                // Replace selection
                const range = selection.getRangeAt(0);
                range.deleteContents();
                range.insertNode(document.createTextNode(separator + text));
            } else {
                // Append at cursor
                const cursorPos = selection.anchorOffset;
                this.textContent = currentText.slice(0, cursorPos) + separator + text + currentText.slice(cursorPos);
            }
            
            // Move cursor to end of pasted content
            const range = document.createRange();
            range.selectNodeContents(this);
            range.collapse(false);
            selection.removeAllRanges();
            selection.addRange(range);
        });
    </script>
</body>
</html>
